---
날짜: 2024-02-21
넘버: 
태그: 프로그래밍
출처: 
aliases:
---
### 날짜  2024-02-21 14:07

### 태그:

>[!메모]
>

### 원문
---
# JWT 장고로 구현하기
## deku 블로그 정리
### 장고 프로젝트 준비
```sh
$> django-admin startproject django_jwt
...
$> python manage.py createsuperuser
...
```
### 장고 djangorestframework-jwt 설치하기
```sh
$> pip install djangorestframework-jwt
$> pip freeze > requirements.txt
```
### settings.py 설정
```python
REST_FRAMEWORK = {
	'DEFAULT_PERMISSION_CLASSES':(
		'rest_framework.permissions.IsAuthenticated',
	),
	'DEFAULT_AUTHENTICATION_CLASSES':(
		'rest_framework_jwt.authentication.JSONWebTokenAuthentication',
	),
}
```
- 로그인 여부를 확인하는 클래스 설정
	- rest_framework.permissions.IsAuthenticated
- 로그인과 관련된 클래스 설정
	- rest_framework_jwt.authentication.JSONWebTokenAuthentication
```python
JWT_AUTH = {
	'JWT_SECRET_KEY': SECRET_KEY,
	'JWT_ALGORITHM': 'HS256',
	'JWT_ALLOW_REFRESH': True,
	'JWT_EXPIRATION_DELTA': datetime.timedelta(day=7),
	'JWT_REFRESH_EXPRIATION_DELTA': datetime.timedelta(day=7),
}
```
- JWT_SECRET_KEY
	- JWT의 비밀키로 어떤 것을 사용할지 설정
	- 장고의 시크릿키를 가져왔으나, 다른 키를 사용해야 한다.
- JWT_ALGORITHM
	- 암호화에 사용되는 알고리즘
- JWT_ALLOW_REFRESH
	- JWT 토큰 갱신 여부 설정
- JWT_EXPIRATION_DELTA
	- JWT 토큰의 유효 기간을 설정
	- 토큰을 7일 안에 갱신하지 않으면 JWT 토큰을 사용할 수 없음
- JWT_REFRESH_EXPRIATION_DELTA
	- JWT 토큰 갱신의 유효기간 설정
	- 토큰을 28일 후에는 갱신할 수 없음
		- 7일 안에 갱신을 하더라도 만료 28일 후에는 만료되어 로그아웃 처리가 됨
### project의 urls.py 설정
```python
from django.contrib import admin
from django.urls import path, include
from rest_framework_jwt.views import obtain_jwt_token, verify_jwt_token, refresh_jwt_token

urlpatterns = [ 
	path('admin/', admin.site.urls), 
	path('api/token/', obtain_jwt_token), 
	path('api/token/verify/', verify_jwt_token), 
	path('api/token/refresh/', refresh_jwt_token), 
	path('api/gateway/', include('gateway.urls')) ]
```
### app의 urls.py 설정
```python
from django.urls import path
from . import views

urlpatterns = [
	path('gateway/', views.posts, name='gateway'),
]
```
### view 만들기
```python
from rest_framework.decorators import api_view, permission_classes, authentication_classes 
from rest_framework.permissions import IsAuthenticated 
from rest_framework_jwt.authentication import JSONWebTokenAuthentication

@api_view(['GET'])
@permission_classes((IsAuthenticated, ))
@authentication_classes((JSONWebTokenAuthentication, ))
def Users(request):
	users = User.objects.all()
	user_list = serializers.serialize('json', users)
	return HttpResponse(user_list, content_type="text/json-comment-filtered")
```
- `from rest_framework.decorators import api_view, permission_classes, authentication_classes `
	- **djangorestframework**가 제공하는 파이썬 데코레이터
- `@api_view(['GET'])`
	- 데코레이터: 하위에 있는 함수를 실행하기 전에 먼저 실행한다.
	- GET 요청인지 검증한다. 
	- GET이 아니라면 JSON 타입으로 반환한다.
- `@permission_classes((IsAuthenticated, ))`
	- 권한을 체크한다.
	- 로그인의 여부만 체크하는 로직이 들어있다.
- `@authentication_classes((JSONWebTokenAuthentication, ))`
	- JWT를 확인한다.
	- 토큰에 이상이 있으면 에러를 JSON 형식으로 반환한다.
## drf-simplejwt
- drf-jwt는 django 4 버전 이상부터 문제가 있어 사용하지 못한다.
	- smart_text를 import하지 못하는 오류
	- 대체제로 simplejwt를 사용한다.
- 이 친구는 ugettext를 import 하지 못한다.

---
### 생각(파생된 질문/생각)

### 출처
- 블로그 레퍼런스
	- https://deku.posstree.com/ko/django/jwt/
- 구현 사례 레퍼런스
	- https://github.com/dev-yakuza/django_jwt?tab=readme-ov-file#django_jwt%E8%AA%AC%E6%98%8E
- django auth
	- https://velog.io/@swhan9404/django%EC%9D%98-Auth-%EB%A1%9C%EA%B7%B8%EC%9D%B8-%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85-%EB%93%B1
- drf-simplejwt
	- https://django-rest-framework-simplejwt.readthedocs.io/en/latest/getting_started.html
### 연결 문서 (연결 이유)
- [[장고 데코레이터]]: 보기만 했지 어떻게 작동하는 것인지 모른다.