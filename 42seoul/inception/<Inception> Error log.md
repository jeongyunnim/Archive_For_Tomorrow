---
날짜: '"2023-12-03"'
넘버: 
태그: 프로그래밍/도커
출처: 
aliases:
---
### 날짜  2023-12-03 21:15

### 태그:

>[!메모]
>

### 원문
---
###  환경변수가 전달되지 않던 상황
- 빌드 과정에서 실행한 쉘 스크립트는 환경변수를 전달받지 못한다.
- 따라서 RUN 대신 CMD 또는 ENTRYPOINT 를 이용해서 빌드된 후 실행할 명령에 쉘 스크립트를 넣어주어야 한다.
### COPY한 디렉토리에 마운트를 했더니 쉘 스크립트가 보이지 않음.

^f47ac7

- 빌드 과정에서 COPY를 한 뒤, 비어있는 로컬 디렉토리에 마운트되면서 사라지는 것 같다.
	- COPY하는 장소를 마운트하는 곳과 다른 곳으로 변경하기
	- 볼륨 마운트를 사용하기.
### mariadb 문법 오류
```error
ERROR: 1064  You have an error in your SQL syntax; check the manual that corresponds to your MariaDB server version for the right syntax to use near 'CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci;' at line 1
```
- 문법 공부 겉핥기로
### 빌드 어떻게 해야할지 모르겠음
```
docker-compose -f ./srcs/compose.yaml build --no-cache
[+] Building 15.5s (36/38)                                                                                                                                                                                                                
 => [wordpress internal] load build definition from Dockerfile                                                                                                                                                                       0.0s
 => => transferring dockerfile: 799B                                                                                                                                                                                                 0.0s
 => [nginx internal] load build definition from Dockerfile                                                                                                                                                                           0.0s
 => => transferring dockerfile: 692B                                                                                                                                                                                                 0.0s
 => [mariadb internal] load build definition from Dockerfile                                                                                                                                                                         0.0s
 => => transferring dockerfile: 610B                                                                                                                                                                                                 0.0s
 => [wordpress internal] load .dockerignore                                                                                                                                                                                          0.0s
 => => transferring context: 34B                                                                                                                                                                                                     0.0s
 => [nginx internal] load .dockerignore                                                                                                                                                                                              0.0s
 => => transferring context: 34B                                                                                                                                                                                                     0.0s
 => [mariadb internal] load .dockerignore                                                                                                                                                                                            0.0s
 => => transferring context: 34B                                                                                                                                                                                                     0.0s
 => [nginx] resolve image config for docker.io/docker/dockerfile:1                                                                                                                                                                   2.2s
 => [wordpress] docker-image://docker.io/docker/dockerfile:1@sha256:ac85f380a63b13dfcefa89046420e1781752bab202122f8f50032edf31be0021                                                                                                13.1s
 => => resolve docker.io/docker/dockerfile:1@sha256:ac85f380a63b13dfcefa89046420e1781752bab202122f8f50032edf31be0021                                                                                                                 0.0s
 => => sha256:ac85f380a63b13dfcefa89046420e1781752bab202122f8f50032edf31be0021 8.40kB / 8.40kB                                                                                                                                       0.0s
 => => sha256:657fcc512c7369f4cb3d94ea329150f8daf626bc838b1a1e81f1834c73ecc77e 482B / 482B                                                                                                                                           0.0s
 => => sha256:a17ee7fff8f5e97b974f5b48f51647d2cf28d543f2aa6c11aaa0ea431b44bb89 1.27kB / 1.27kB                                                                                                                                       0.0s
 => => sha256:9d9c93f4b00be908ab694a4df732570bced3b8a96b7515d70ff93402179ad232 11.80MB / 11.80MB                                                                                                                                     0.6s
 => => extracting sha256:9d9c93f4b00be908ab694a4df732570bced3b8a96b7515d70ff93402179ad232                                                                                                                                            0.2s
 => [wordpress internal] load build definition from Dockerfile                                                                                                                                                                       0.0s
 => [nginx internal] load metadata for docker.io/library/alpine:3.17                                                                                                                                                                 1.8s
 => [nginx internal] load build definition from Dockerfile                                                                                                                                                                           0.0s
 => [mariadb internal] load build definition from Dockerfile                                                                                                                                                                         0.0s
 => [wordpress internal] load .dockerignore                                                                                                                                                                                          0.0s
 => [mariadb internal] load .dockerignore                                                                                                                                                                                            0.0s
 => [nginx internal] load .dockerignore                                                                                                                                                                                              0.0s
 => [wordpress 1/7] FROM docker.io/library/alpine:3.17@sha256:6e94b5cda2d6fd57d85abf81e81dabaea97a5885f919da676cc19d3551da4061                                                                                                      10.3s
 => => resolve docker.io/library/alpine:3.17@sha256:6e94b5cda2d6fd57d85abf81e81dabaea97a5885f919da676cc19d3551da4061                                                                                                                 0.0s
 => => sha256:b6e5fbdf7e79701eb7c3b82928089980986395a8ab16f96cdc6e6874f618b375 528B / 528B                                                                                                                                           0.0s
 => => sha256:7997ad530b088ce1ef0b5e4a705600db0e62a2fd399e3639722b81ebe596d67d 1.47kB / 1.47kB                                                                                                                                       0.0s
 => => sha256:1207c741d8c9b028d98c4006013f9de959da3c55f85b91ed5e4583438a0112ca 3.38MB / 3.38MB                                                                                                                                       0.3s
 => => sha256:6e94b5cda2d6fd57d85abf81e81dabaea97a5885f919da676cc19d3551da4061 1.64kB / 1.64kB                                                                                                                                       0.0s
 => => extracting sha256:1207c741d8c9b028d98c4006013f9de959da3c55f85b91ed5e4583438a0112ca                                                                                                                                            0.1s
 => [nginx internal] load build context                                                                                                                                                                                              0.0s
 => => transferring context: 5.24kB                                                                                                                                                                                                  0.0s
 => [wordpress internal] load build context                                                                                                                                                                                          0.0s
 => => transferring context: 1.15kB                                                                                                                                                                                                  0.0s
 => [mariadb internal] load build context                                                                                                                                                                                            0.0s
 => => transferring context: 2.31kB                                                                                                                                                                                                  0.0s
 => [mariadb 2/6] RUN apk --no-cache update && apk add mysql mysql-client                                                                                                                                                            8.3s
 => [wordpress 2/8] RUN apk update &&    apk --no-cache add php php-fpm php-phar php-curl php-mysqli                                                                                                                                 3.2s
 => [nginx 2/7] RUN apk update &&     apk --no-cache add nginx     openssl &&     adduser -D wordpress                                                                                                                               2.2s
 => [nginx 3/7] WORKDIR /etc/ssl/private/                                                                                                                                                                                            0.0s
 => [nginx 4/7] RUN openssl genrsa -out jeseo.42.fr.key 2048 &&    openssl req -new -key jeseo.42.fr.key -out jeseo.42.fr.crt     -subj "/C=KR/ST=Seoul/L=Gaepodong/O=42seoul/OU=Cadet/CN=jeseo.42.kr" &&    openssl x509 -req -day  0.4s
 => [nginx 5/7] COPY ./tools/nginx.conf /etc/nginx/nginx.conf                                                                                                                                                                        0.0s
 => [nginx 6/7] COPY ./tools/default.conf /etc/nginx/http.d/default.conf                                                                                                                                                             0.0s
 => [nginx 7/7] COPY ./tools/ /var/www/html/                                                                                                                                                                                         0.0s
 => [mariadb] exporting to image                                                                                                                                                                                                     1.0s
 => => exporting layers                                                                                                                                                                                                              0.8s
 => => writing image sha256:e6a7145c14498e973f7f723b8dc14be45b38a559914ba607873625f2de861c9a                                                                                                                                         0.0s
 => => naming to docker.io/library/nginx                                                                                                                                                                                             0.0s
 => => writing image sha256:7b0f5c4c4eff1bb13d89f4348541df5f8b72519d4ee0fb4bf51424258e323391                                                                                                                                         0.0s
 => => naming to docker.io/library/wordpress                                                                                                                                                                                         0.0s
 => => writing image sha256:dea92ad0365bd3f473f4bd4de9871a32167a63134e429de9656090ffb591beac                                                                                                                                         0.0s
 => => naming to docker.io/library/mariadb                                                                                                                                                                                           0.0s
 => [wordpress 3/8] RUN sed -i "s|listen = 127.0.0.1:9000|listen = 0.0.0.0:9000|g" /etc/php81/php-fpm.d/www.conf                                                                                                                     0.2s
 => [wordpress 4/8] WORKDIR /var/www/html                                                                                                                                                                                            0.0s
 => [wordpress 5/8] RUN wget https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar &&    php wp-cli.phar &&    chmod +x wp-cli.phar &&    mv wp-cli.phar /usr/local/bin/wp                                       0.6s
 => [wordpress 6/8] COPY ./tools/set_wp_config_file.sh /var/www/html/set_wp_config_file.sh                                                                                                                                           0.0s
 => [wordpress 7/8] COPY ./tools/install_wp.sh /var/www/html/install_wp.sh                                                                                                                                                           0.0s
 => [wordpress 8/8] RUN chmod +x /var/www/html/set_wp_config_file.sh &&     chmod 777 /var/www/html/install_wp.sh &&     /bin/sh /var/www/html/set_wp_config_file.sh                                                                 0.2s
 => [mariadb 3/6] RUN mkdir /var/run/mysqld &&     chmod 755 /var/run/mysqld &&     sed -i "s|.*bind-address\s*=.*|bind-address=0.0.0.0|g" /etc/my.cnf.d/mariadb-server.cnf &&    sed -i "s|.*skip-networking.*|skip-networking|g"   0.3s
 => [mariadb 4/6] COPY tools/wordpress_setup.sql /home/                                                                                                                                                                              0.0s
 => [mariadb 5/6] COPY tools/set.sh /home/                                                                                                                                                                                           0.0s
 => [mariadb 6/6] RUN chmod 755 /home/set.sh 
 Use 'docker scan' to run Snyk tests against images to find vulnerabilities and learn how to fix them
docker compose -f ./srcs/compose.yaml up -d 
[+] Running 2/4
 ⠿ Network mynet      Created                                                                                                                                                                                                        0.0s
 ⠿ Container mydb     Created                                                                                                                                                                                                        0.0s
 ⠋ Container mynginx  Creating                                                                                                                                                                                                       0.0s
 ⠋ Container mywp     Creating                                                                                                                                                                                                       0.0s
Error response from daemon: failed to copy files: failed to open target /var/lib/docker/volumes/srcs_wp-vol/_data/default.conf: open /var/lib/docker/volumes/srcs_wp-vol/_data/default.conf: no such file or directory
 ```
`open /var/lib/docker/volumes/srcs_wp-vol/_data/default.conf`
- 이건 도대체 누가 하는 거임? 빌드도 잘 됐는데 왜 지랄인지 모르겠음. 




---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)