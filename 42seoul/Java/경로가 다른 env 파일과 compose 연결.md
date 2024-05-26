---
날짜: 2024-05-25
넘버: 
태그: 프로그래밍/도커
출처: https://docs.docker.com/compose/environment-variables/set-environment-variables/
aliases:
---
### 날짜:  2024-05-25 13:29

### 태그: #프로그래밍/도커 

>[!메모]
> compose 옵션을 설정하다가 발견

### 원문
---
# 경로가 다른 env 파일과 compose 연결
- compose에 default 경로(`./`)가 아닌 다른 경로의 env파일을 연결할 때 context를 전달하는 방법
- https://docs.docker.com/compose/environment-variables/set-environment-variables/

- `env_file` 디렉티브
- `compose --env-file file/path up` 옵션 넣어서 compose up

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
