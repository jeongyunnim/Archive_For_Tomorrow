---
날짜: '"2023-12-09"'
넘버: 
태그: 프로그래밍/데이터베이스
출처: 
aliases:
---
### 날짜  2023-12-09 15:21

### 태그: #프로그래밍/데이터베이스

>[!메모]
>

### 원문
---
```mysql
USE mysql;
FLUSH PRIVILEGES;

DELETE FROM mysql.user WHERE User='';
DROP DATABASE test;
DELETE FROM mysql.db WHERE Db='test';
DELETE FROM mysql.user WHERE User='root' AND Host NOT IN ('localhost', '127.0.0.1', '::1');
ALTER USER 'root'@'localhost' IDENTIFIED BY '${MYSQL_ROOT_PASSWORD}';
CREATE DATABASE IF NOT EXISTS ${MYSQL_DATABASE};
CREATE USER '${MYSQL_USER}'@'%' IDENTIFIED BY '${MYSQL_PASSWORD}';
GRANT ALL PRIVILEGES ON ${MYSQL_DATABASE}.* TO '${MYSQL_USER}'@'%';
FLUSH PRIVILEGES;
```
- `USE mysql`
	- mysql 데이터베이스를 사용하겠다는 의미
- `FLUSH PRIVILEGES`
	- 이전에 부여한 권한을 적용함.
- `DLETE FROM mysql.user WHERE User=''`
	- 빈 문자열로 구성된 유저를 삭제해줌.
	- [[mariadb 설치 후에 생성이 되어있는 유저는 왜 생기는지는 모르겠음]]
- `DROP DATABASE test;`
	- test 데이터베이스를 삭제함
- `DELTE FROM mysql.db WHERE Db='test`'
	- test 데이터베이스에 대한 정보를 'mysql.db' 테이블에서 삭제함.
- `DELETE FROM mysql.user WHERE User='root' AND Host NOT IN {'localhost', '127.0.0.1', '::1'}`
	- 테이블에서 사용자 이름이 root이면서 호스트가 localhost, 127.0.0.1, ::1이 아닌 것을 삭제한다.
	- 원격 접속을 막고 로컬에서만 접속을 허용하는 것.
- `ALTER USER 'root'@'localhost' IDENTIFIED BY '${MYSQL_ROOT_PASSWORD}'`
	- root 사용자의 localhost에서의 암호를 변경
- `CREATE DATABASE IF NOT EXISTS ${MYSQL_DATABASE}`
	- 데이터베이스가 존재하지 않으면 생성해줌
- `CREATE USER '${MYSQL_USER}'@'% IDENTIFIED BY '${MYSQL_PASSWORD}'`
	- %(모든 호스트에서) 유저를 생성하고 비밀번호를 설정함
- `GRANT ALL PRIVIEGES ON ${MYSQL_DATABASE}.* TO '${MYSQL_USER}'@'%'`
	- 데이터베이스에 대한 모든 권한을 모든 호스트에서 MYSQL_USER에게 부여함.


---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
