---
날짜: 2024-06-02
넘버: 
태그: 프로그래밍
출처: 
aliases:
---
### 날짜:  2024-06-02 18:32

### 태그: #프로그래밍 

>[!메모]
>

### 원문
---
# 개발 과정에서 발생한 에러
### ✅build context로 env path 전달 오류
```sh
docker compose -f ./compose.yaml down --volumes
```
- env 파일을 각 compose에서 `env_file:`로 전달하고 있기 때문에 `--env-file`를 제거 했었다.
- 하지만 compose 빌드 환경에서 사용하는 환경변수를 찾을 수 없는 오류가 발생했다.
#### 해결
```sh
docker compose --env-file ./env/.env -f ./compose.yaml down --volumes
```
- 결국 compose에도 전달해야 하고, 각 서비스의 빌드 환경에도 전달해야 했다.

### ✅Dockerfile context와 compose의 context
- 도커파일의 `ARG`에 path를 지정해 놓은 부분
```dockerfile
ARG JAR_FILE=build/libs/*.jar
```
- compose context로 전달하기 위해 아래와 같이 변경했다.
```dockerfile title:Dockerfile
ARG JAR_FILE
```
- compose 설정
```yaml title:compose.yaml
build:
	context: ./BE/path
	args:
		- JAR_FILE=./BE/path/build/libs/*.jar
```
- 오히려 해당 path를 찾아가지 못하는 오류가 발생했다.
#### 해결
```Dockerfile
ARG JAR_FILE=build/libs/*.jar
```
- Dockerfile context가 유지 되기 때문에 이 부분은 문제가 되지 않았다.
### ✅Dockerfile 누락
```error
=> CANCELED [gateway internal] load metadata for docker.io/library/openjdk:17-jdk 0.0s failed to solve: failed to read dockerfile: open /var/lib/docker/tmp/buildkit-mount4111699833/Dockerfile: no such file or directory make[1]: *** [up] Error 17
```
- FE-PINTING에 Dockerfile이 없어서 생기는 오류였다.
#### 해결
- FE-PINTING을 제외하고 컨테이너를 올려서 해결.
- 이후 프론트 쪽 Dockerfile이 업로드 되면 추가해야 함.
### ✅컨테이너를 찾지 못하는 오류
```
nginx: [emerg] host not found in upstream "gateway" in /etc/nginx/http.d/default.conf:14
```
- gateway보다 nginx 컨테이너가 먼저 실행되기 때문에 생긴 오류였다.
#### 해결
```yaml
depens_on: 
	- gateway
```
### ✅port 중첩
```error
Error response from daemon: driver failed programming external connectivity on endpoint web-proxy (b412968a0a9f3cb76cc20cd70c3ff7f40b95ddf904b80dea1d0652ef9896a38a): Bind for 0.0.0.0:8080 failed: port is already allocated
```
- 톰캣 서버 실행 시 default가 8080으로 실행되기 때문에 nginx로 열어놓은 8080과 충돌하는 오류가 발생했다.
#### 해결
- 포트를 변경하여 해결.
### redirect uri가 api로 이어지지 않아서 발생하는 오류
![[Pasted image 20240602185517.png]]
- Spring security가 진입점의 가장 앞단에 있기 때문에 어떤 API도 로그인으로 유도가 되고 있는 것같다.
- redirect_uri를 `pinting.com/api`로 잘 전달하면 해결될 문제로 보인다.
### 리다이렉트 시 포트가 누락되는 문제 발생
- 위의 사진 처럼 gateway로는 연결이 들어가지만 포트번호가 누락되는 문제가 발생.
- redirect를 모두 변경하여 요청해봤지만, 해결하지 못함.
- nginx가 문제인 줄 알았지만, JWT doFilter 로직에서 null 체크를 해주니 문제가 다시 해결 됨.
![[Pasted image 20240604205228.png]]

> [!tip]
> `<local6>`가 null이라는 예외가 자꾸 발생했는데, 이는 자바가 내부적으로 지역 변수를 이렇게 설정하고 있는 것이었다.

### like를 엔티티 이름으로 사용할 수 없는 오류
```log
could not execute statement [ERROR: syntax error at or near "like"
  Position: 55] [/* insert for pinting.board.domain.Like */insert into like (member_id,post_id,like_id) values (?,?,?)]
org.hibernate.exception.SQLGrammarException: could not execute statement [ERROR: syntax error at or near "like"
  Position: 55] [/* insert for pinting.board.domain.Like */insert into like (member_id,post_id,like_id) values (?,?,?)]
	at org.hibernate.exception.internal.SQLStateConversionDelegate.convert(SQLStateConversionDelegate.java:91)
	...
```
- like에 대한 문법 오류가 났다고 해서 Entity의 이름을 SQL 예약어로 사용할 수 없다는 것을 떠올렸다.
- @Table(name = "likes")로 문제를 회피해야 한다.
---
## compose 파일 설정 - 데이터베이스
![[Pasted image 20240723203705.png]]
- role 또는 database가 없음.
- 포트번호 5432(디폴트)로 연결했는지 확인해야 함.
	- 바인딩만 다르게 한 경우..
- pg_isready는 옵션 먹통임 이상함. 환경변수만 따라감.
		- `PGUSER`, `PGDATABASE`
- application에서 yaml 중복되는 게 있다면 컴파일 오류 발생한다.
- postgres는 dialect 설정을 해주지 않아도 된다.
---
# JIB
### 변경 사항이 적용 안 되는 문제
detail: 변경사항을 넣어서 빌드를 했지만 시도한 모든 방법이 모두 이전과 같은 결과를 내었다.
설마 이미지 파일이 업데이트 되고 있지 않은 것은 아닌가 것인가 싶어서 다시 빌드를 했더니 문제가 이미 해결이 되어있었다.
- 결론 
	- 빌드를 새로해야 한다면 이미지도 지우자.
	- 만약 이미지가 문제가 아니더라도, 문제의 여지를 최소화하는 것이 좋을 것 같다.
![[Pasted image 20240723231732.png]]
[이미지 출처](https://github.com/GoogleContainerTools/jib/issues/413)

### 도커 이미지가 멀티 플랫폼을 지원하지 않아 발생하는 문제
![[Pasted image 20240730195848.png]]
- m1 에서는 amd64 플랫폼을 주석처리하고 돌리면 문제가 해결이된다.
	- 근본적인 문제를 해결하기 위해서는 도커 이미지 빌드를 멀티 플랫폼을 지원하도록 하는 것이 좋을 것 같다.
	- [[멀티 플랫폼에서 도커 이미지 빌드]]
### Grafana loki gateway(Nginx) `docker-entrypoint.sh` not found 에러
- latest는 해당 파일이 없다.
	- 1.25.5 버전을 직접 지정해주어야 한다.
	- 업데이트할 때 무엇이 바뀌었는지는 나중에 알아보자.
### Grafana javaagent dependency 추가 에러
- 공식 홈페이지에서는 dependency 정보를 제공하지 않는다.
	- Maven repository에서 opentelemetry javaagent를 검색하여 찾아야한다.
	- 어떤 레퍼런스에서 이 정보를 제공하는지 알아봐야 한다.
	- 공식 홈페이지에서는 jar를 직접 받아서 이미지에 COPY해 넣는 것을 추천하고 있다.

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
