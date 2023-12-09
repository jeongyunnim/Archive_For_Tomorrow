---
날짜: '"2023-11-14"'
넘버: 
태그: 42subject
출처: https://infraadmin.tech/blog/docker-alpine-linux%ec%97%90-wordpress-%ec%84%a4%ec%b9%98%ed%95%98%ea%b8%b0/
aliases:
---
### 날짜  2023-11-14 15:22

### 태그: #42subject 

>[!메모]
> 

### 원문
---
## 1. 환경 설명
- DBMS(DataBase Management System): MariaDB
- 고도화 구성
	- HaProxy 설치 및 SSL 인증서 적용
	- 이미지 파일용 CDN 분리
	- File Server(로컬 저장소)분리
	- AutoScale 적용
	- Mini Kubernetes 적용
	- 로그 모니터링
## 2. HostOS Ubuntu 20.04 설치
- VM을 통해 설치파일([[ISO]])로 Ubuntu를 설치한다.
```bash
apt-get update && upgrade
apt update && upgrade

apt install net-tools
apt install ssh
```
- 특정 포트로 [[포트포워딩]]을 한다.
## 3. Ubuntu에 Docker 설치
```bash
sudo apt-get install ca-certificates curl gnupg lsb-release
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
apt-get update
apt-get install docker-ce docker-ce-cli containerd.io
```
참조: [Install Docker Engine on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
## 4. Ubuntu에  컨테이너용 Storage Directory 생성
컨테이너가 실행중일떄 컨테이너 내부에 적재되는 데이터를 휘발성 데이터이므로 데이터 적재가 필요한 경우 스토리지 마운트를 따로 지정해준다.
```bash
mkdir -p /docker/wordpress/config # Dockerfile, lighhtpd.conf, index.php
mkdir -p /docker/wordpress/data # wordpress home directory
```
## 5. WordPress Dockerfile 설정
```dockerfile
#/docker/wordpress/config/Dockerfile
#Alpine Linux OS를 기반으로 한다.
FROM alpine:3.15
RUN apk update

#Wordpress설치에 필요한 패키지
RUN apk add lighttpd php7-common php7-session php7-iconv php7-json php7-gd php7-curl php7-xml php7-mysqli php7-imap php7-cgi fcgi php7-pdo php7-pdo_mysql php7-soap php7-xmlrpc php7-posix php7-mcrypt php7-gettext php7-ldap php7-ctype php7-dom php7-simplexml php7-zip

#php.ini file upload size
RUN sed -ri 's/upload_max_filesize = 2M/upload_max_filesize = 4M/g' /etc/php7/php.ini

#php에서 사용하는 Memory 사용량 증설
RUN sed -ri 's/memory_limit = 128M/memory_limit = 256M/g' /etc/php7/php.ini

#lighttpd.conf -> 아마도 nginx쪽으로 바꿔야할 것.
#COPY lighttpd.conf /etc/lighttpd/lighttpd.conf

#index.php
#COPY index.php /var/www/localhost/htdocs/index.php

#PID
RUN mkdir /run/lighttpd
RUN chown -R lighttpd /run/lighttpd

#Foreground
CMD ["lighttpd", "-f", "/etc/lighttpd/lighttpd.conf", "-D"]
```
- WordPress를 다운로드 받는다.
```bash
#Docker build (Dockerfile) /docker/wordpress/config
docker build -t infraadmin.tech:1.0 /docker/wordpress/config/

#wordpress_app 컨테이너를 백그라운드 데몬으로 http 포트를 연동하여 실행한다. HostOS인 Ubuntu의 /docker/wordpress/data 폴더를 컨테이너의 wordpress 폴더에 마운트한다. 이미지는 infraadmin.tech:1.0을 사용한다.
docker run -d --name wordpress_app -p 80:80 -v /docker/wordpress/data:/var/www/localhost/htdocs/wordpress infraadmin.tech:1.0
```
- 최초 1회만 필요하므로 Dockerfile을 이용하지 않는다.
```bash
docker ps
docker exec -it {CONTAINER ID} /bin/sh
cd /var/www/localhost/htdocs
wget http://wordpress.org/latest.tar.gz
tar -xzvf latest.tar.gz
rm latest.tar.gz
#default lighttpd.conf는 관리를 위해 HostOS로 복사해온다.
cp /etc/lighttpd/lighttpd.conf /var/www/localhost/htdocs/wordpress
exit
```
## 6. lighttpd 설정
```bash
mv /docker/wordpress/data/lighttpd.conf /docker/wordpress/config/
vi /docker/wordpress/config/lighttpd.conf
```

```bash
vi /docker/wordpress/config/Dockerfile
```

```bash
#include "mod_fastcgi.conf" 주석제거
server.modules = (

   include "mod_fastcgi.conf"
```

```bash
#COPY lighttpd.conf 주석제거
#lighttpd.conf
COPY lighttpd.conf /etc/lighttpd/lighttpd.conf"
```
- 실행 중인 컨테이너를 중지하고 다시 빌드한다.
## 7. WordPress 컨테이너
- http 연결을 위해 포트포워딩을 추가한다.
## 8. WordPress 실행 확인
- ddns 주소로 들어가면 wordpress 초기 설정 화면을 볼 수 있다.

[[Alpine Linux에 WordPress MariaDB 설치하기|mariaDB 설치하기]]

---
### 생각(파생된 질문/생각)

### 출처
- https://infraadmin.tech/blog/docker-alpine-linux%ec%97%90-wordpress-%ec%84%a4%ec%b9%98%ed%95%98%ea%b8%b0/
- https://wiki.alpinelinux.org/wiki/WordPress

### 연결 문서 (연결 이유)
