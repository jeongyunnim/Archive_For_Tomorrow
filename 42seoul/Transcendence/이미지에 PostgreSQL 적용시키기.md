---
날짜: '"2024-02-10"'
넘버: 
태그: 프로그래밍/도커
출처: 
aliases:
---
### 날짜  2024-02-10 19:37

### 태그:

>[!메모]
>

### 원문
---
# 이미지에 PostgreSQL 적용시키기
- 먼저 출처의 방식대로 도커 파일에 작성을 해주고 있다.
- initdb가 무엇인고.
```sh
mkdir /var/lib/postgresql/data
chmod 0700 /var/lib/postgresql/data
initdb -D /var/lib/postgresql/data/
echo "host all all 0.0.0.0/0 md5" >> /var/lib/postgresql/data/pg_hba.conf
echo "listen_addresses='*'" >> /var/lib/postgresql/data/postgresql.conf
pg_ctl start -D /var/lib/postgresql/data
```

---
### 생각(파생된 질문/생각)

### 출처
- https://luppeng.wordpress.com/2020/02/28/install-and-start-postgresql-on-alpine-linux/

### 연결 문서 (연결 이유)
