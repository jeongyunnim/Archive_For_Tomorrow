---
날짜: '"2023-11-14"'
넘버: 
태그: 프로그래밍
출처: "NGINX 쿡북: 112가지 레시피로 배우는 고성능 부하분산, 보안, 서버 배포와 관리"
저자: 데릭 디용기
aliases:
---
### 날짜  2023-11-14 20:58

### 태그:

>[!메모]
>

### 원문
---
## 1.4 설치 상태 점검
- nginx 명령으로 설정을 시험하거나 마스터 프로세스에 신호(signal)을 보낼 수 있다.
- nginx의 기본 설정은 80번 포트로 접근하는 정적 기본 HTTP 페이지를 제공한다.
## 1.5 주요 설정 파일 
> 엔진엑스 주요 디렉터리 구조와 명령어 이해하기
### 엔진엑스 주요 설정 파일과 디렉터리
- `/etc/nginx/`
	- nginx 서버가 사용하는 기본 설정이 저장된 루트 디렉터리. 
	- nginx는 이곳에 저장된 설정 파일의 내용에 따라 동작한다.
- `/etc/nginx/nginx.conf`
	- 엔진엑스의 기본 설정 파일
	- 모든 설정에 대한 진입점.
		- 워커 프로세스 개수
		- 튜닝
		- 동적 모듈 적재
		- 글로벌 설정 항목
	- 다른 nginx 세부 설정 파일에 대한 참조를 지정
	- 모든 설정 파일을 포함하는 최상위 http블록을 갖고있다.
- `/etc/nginx/conf.d/`
	- 기본 HTTP 서버 설정 파일을 포함한다.
	- 디랙터리 내 파일 중 .conf 확장자를 가진 파일은 nginx.conf 파일이 가진 최상위 http 블록에 포함된다.
	- nginx 설정은 include 구문을 활용하므로, 각 설정 파일을 간결하게 유지하는 것이 좋다.
- `/var/log/nginx`
	- nginx의 로그가 저장되는 디렉터리
		- access.log 
		- error.log
### 엔진엑스 명령어 
- nginx -h
	- 도움말
- nginx -v
	- 버전 정보 확인
- nginx -V
	- 버전 정보 + 빌드 정보 + nginx 바이너리에 포함된 모듈을 보여주는 설정 인수값을 확인
- nginx -T
	- nginx 설정을 시험하고 결과를 화면에 보여줌.
- nginx -s signal
	- 지정된 신호(stop, quit, reload, reopen)를 엔진엑스 마스터 프로세스에 전송한다.
## 1.7 무중단 설정 리로드
> 패킷 손실 없이 설정 리로드하기
```bash
nginx -s reload
```
- 패킷 손실 없이 설정 변경.
- 높은 가용성이 필요한 환경에서 부하분산 설정을 변경해야 하는 경우가 빈번할 수 있다.
- 동적으로 설정 가능한 애플리케이션 인식 모듈이나 클러스터 인식 모듈을 구축하여 무중단으로 엔진엑스 설정을 리로드 한다.
## 6.1 HTTP 기본 인증
> HTTP 기본 인증을 이용해 애플리케이션과 콘텐츠를 안전하게 보호하기
``` plaintext
# 주석
name1:password1
name2:password2:comment
name3:password3
```
- 각 필드 설명
	- 첫 번째 필드:사용자 이름
	- 두 번째 필드: 비밀번호
	- 세 번째 필드: 주석
		- 사용자에 대해 기록해둘 내용이 있을 경우 주석을 단다.
- 필드는 콜론으로 구분한다.
- openssl을 통해 사용하는 passwd또한 내부적으로 crypt()를 통해 구현되어있다.
```bash
$ openssl passwd MyPassword1234
```
이를 실행하면 암호화된 문자열을 얻으며 엔진엑스 비밀번호 파일에 그대로 사용할 수 있다.

## 7.4 고급 클라이언트 측 암호화
- 엔진엑스 SSL 모듈은 수신된 요청과 SSL/TLS 연결 협상을 제어한다.
- 인증서와 키 파일은 변수나 파일 경로 값을 통해 엔진엑스 설정에 사용할 수 있다.
- 엔진엑스는 설정된 내용에 따라 클라이언트에 사용할 수 있는 프로토콜, 암호화 스위트(cipher suite), 키 형식을 제공한다.
```conf
http {
	server {
		listen 8443;
		# 허용할 버전과 암호화 알고리즘 설정
		ssl_protocols TLSv1.2 TLSv1.3;
		ssl_ciphers HIGH:!aNULL:!MD5;
		
		# RSA 인증서 파일 경로 지정
		ssl_certificate /etc/nginx/ssl/example.crt;
		# RSA 암호화 키 파일 경로 지정
		ssl_certificate /etc/nginx/ssl/example.pem;

		#EV(Elliptic Curve) 인증서를 변수에서 불러옴
		ssl_certificate $ecdsa_cert;
		#EV(Elliptic Curve) 키를 파일 경로가 담긴 변수를 참조하여 읽어온다.
		ssl_certificate_key data:$ecdsa_key_path;

		# 클라이언트-서버 간의 SSL/TLS 연결 협상 결과를 캐시
		ssl_session_cache shared:SSL:10m;
		ssl_session_timeout 10m;
	}
}
```
- `ssl_ciphers HIGH:!aNULL:!MD5;`
	- TLS 표준이 제시하는 높은 수준을 사용하도록 HIGH를 지정.
	- aNULL과 MD5는 사용하지 않도록 명시적으로 느낌표를 붙여 지정
		- aNULL: 인증 기능이 없는 암호와 알고리즘
		- 인증기능이 없으면 [[중간자 공격(MITM)]]에 취약하다.
		- MD5는 보안에 취약하다.
			- https://namu.wiki/w/MD5
- 설정에서 인증서 키 두 쌍을 사용하고 있다.
	- 서버가 받아줄 수 있는 가장 강력한 표준이 TLS 연결 협상에 사용된다.
- 나머지 예제 설정
	- 캐시 영역으로 할당 된 10MB 메로리가 허용하는 한 엔진엑스가 SSL/TLS 연결 정보를 최대 10분간 유지하도록 함.
## 7.5 업스트림 암호화
```conf
location / {
	proxy_pass https://upstream.example.com;
	proxy_ssl_vertify on;
	proxy_ssl_vertify_depth 2;
	proxy_ssl_protocols TLSv1.2;
}
```
- proxy 지시자들은 엔진엑스가 준수해야 하는 SSL 규칙을 정의한다.

## 11.4 엔진엑스 도커 파일 생성
- 사용 중인 리눅스 배포판의 엔진엑스 도커 이미지 만들기
	- FRO: 도커 이미지 지정
	- RUN: 엔진엑스를 설치
	- EXPOSE: 도커가 지정된 포트 노출
	- CMD: 엔진엑스 시작

- 엔진엑스를 포어그라운드로 실행해야 하는 경우
	- 엔진엑스 실행 시에 `-g "daemon off;"`로 매개변수를 지정
	- 엔진엑스 설정에 `daemon off;`를 지정
- 엔진엑스 접근 로그를 /dev/stdout으로 보내고 오류 로그를 /dev/strerr로 보내기 위해 엔진엑스 설정을 변경할 필요가 있다.
	- 도커 데몬이 로그 파일들을 다룰 수 있고 도커에서 사용하는 로그 드라이버를 기반ㄴ으로 쉽게 로그를 처리하게 된다.

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)


