---
날짜: '"2023-11-14"'
넘버: 
태그: 42subject
출처: https://infraadmin.tech/blog/docker-alpine-linux%ec%97%90-wordpress-mariadb-%ec%84%a4%ec%b9%98%ed%95%98%ea%b8%b02/
aliases:
---
### 날짜  2023-11-14 16:23

### 태그:

>[!메모]
>

### 원문
---
## 1. 환경 설명
- 알파인에 설치하는 경우는 드물기 때문에 레퍼런스를 찾기 어려움
- Docker Hub의 mariaDB 이미지는 우분투에 필요없는 패키지들이 함께 설치된다(pwgen, tzdata 등)
- WordPress 컨테이너에 DBMS를 구축하는 방법에 대해 알아보자.
## 2. mariaDB Dockerfile 설정
```bash
# alpine 3.15 Version을 기반으로 한다.
FROM alpine:3.15

# no-cache 옵션은 /var/cache/apk/* 에 garbage가 남지 않음.
# alpine3.15 기준 mariadb-10.6.8-r0 LTS
# SQL문을 직접 넣기위해 client 필요
# /etc/init.d/mariadb setup 이후 mysqld 재시작을 위해 openrc 필요
RUN apk add --no-cache mariadb mariadb-client openrc

# mysql_secure_installation 설정이 담긴 sql쿼리문
COPY mysql_secure_installation.sql /home/

# sql server 설정 since alpine 3.9 First Global config file, main directives
COPY mariadb-server.cnf /etc/my.cnf.d/

# wordpress database 설정
COPY create_wordpressdb_user.sql /home/

# sql 시작 스크립트
COPY start_mariadb.sh /home

VOLUME ["/var/lib/mysql"]

# DBMS포트는 8475를 사용한다.
EXPOSE 8475
ENTRYPOINT sh /home/start_mariadb.sh
```



---
### 생각(파생된 질문/생각)

### 출처
- 
### 연결 문서 (연결 이유)
- https://wiki.alpinelinux.org/wiki/MariaDB