---
날짜: '"2023-12-09"'
넘버: 
태그: 프로그래밍/데이터베이스
출처: https://dev.mysql.com/doc/refman/5.7/en/data-directory.html
aliases:
---
### 날짜  2023-12-09 16:02

### 태그:

>[!메모]
>

### 원문
---
# The MySQL Data Directory
서버에서 관리하는 정보는 data 디렉토리에 저장된다.
### 데이터 디렉토리의 하위 디렉토리
- 서버에서 관리하는 데이터베이스에 해당됨.
- mysql 디렉토리
	- MySQL 서버가 실행할 때 필요한 정보가 들어있는 시스템 데이터베이스
	- [자세한 정보](https://dev.mysql.com/doc/refman/5.7/en/system-schema.html)
- performance_schema 디렉토리
	- 런타인에 서버 내부 실행을 검사하는 데 사용되는 정보를 제공함
	- [자세한 정보](https://dev.mysql.com/doc/refman/5.7/en/performance-schema.html)
- sys 디렉토리
	- 성능 스키마 정보를 쉽게 해석하는 데 도움이되는 정보를 제공
	- [자세한 정보](https://dev.mysql.com/doc/refman/5.7/en/sys-schema.html)
- INFORMATION_SCHEMA는 표준 데이터베이스이나 그 구현은 해당 데이터베이스 디렉터리를 사용하지 않는다.
	- InnoDB 스토리지 엔진을 사용하는 MySQL은 해당 데이터베이스가 특별한 역할을 한다.
	- MySQL 서버의 메타데이터 및 시스템 정보를 저장하는 **가상의 데이터베이스**이다.
	- 일반적인 데이터베이스와 달리 데이터를 실제로 저장하지 않는다.
	- 서버의 상태 및 구성 정보를 쿼리할 수 있도록 한다.
- 예시 
```sql
SELECT table_name FROM information_schema.tables WHERE table_schema = 'your_database_name';
```
이런 식으로 서버의 구조와 상태에 대한 정보를 동적으로 쿼리할 수 있다.

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
