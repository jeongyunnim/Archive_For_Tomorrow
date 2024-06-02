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
- TODO: 이후 프론트 쪽 Dockerfile이 업로드 되면 추가해야 함.
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
### ✅redirect uri가 api로 이어지지 않아서 발생하는 오류
![[Pasted image 20240602185517.png]]
- Spring security가 진입점의 가장 앞단에 있기 때문에 어떤 API도 로그인으로 유도가 되고 있는 것같다.
- redirect_uri를 `pinting.com/api`로 잘 전달하면 해결될 문제로 보인다.
---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
