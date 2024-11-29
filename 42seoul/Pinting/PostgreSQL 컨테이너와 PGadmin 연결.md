---
날짜: 2024-11-29
넘버: 
태그: 
출처: 
aliases:
---
### 날짜:  2024-11-29 17:15

### 태그:

>[!메모]
>

### 원문
---
# PostgreSQL 컨테이너와 PGadmin 연결
- PostgrSQL 컨테이너 실행
	- 프로젝트 내부라면 compose 파일을 통해서 실행하는 것이 적합하다.
	- mount를 로컬에 해주어야 데이터가 정상적으로 저장될 것이다.
```sh
docker run -d -e POSTGRES_PASSWORD=password -p 5431:5432 postgres:16.3-alpine3.20
```
- PGadmin 실행
	- Server에 등록해준다.
![[Pasted image 20241129171518.png]]
- 표시할 이름 입력
![[Pasted image 20241129171835.png]]
- 연결할 컨테이너의 접속 정보를 입력한다.
	- host name / password / username
	- 현재 localhost:5432의 포트가 사용 중이었기 때문에 localhost:5431로 연결했다.
![[Pasted image 20241129171928.png]]


---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
