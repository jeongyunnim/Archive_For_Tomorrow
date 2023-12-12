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
### 환경변수가 전달되지 않던 상황
#### 해결
- 빌드 과정에서 실행한 쉘 스크립트는 환경변수를 전달받지 못한다.
- 따라서 RUN 대신 CMD 또는 ENTRYPOINT 를 이용해서 빌드된 후 실행할 명령에 쉘 스크립트를 넣어주어야 한다.
---
### COPY한 디렉토리에 마운트를 했더니 쉘 스크립트가 보이지 않음.
- [x] 해결 여부
- 빌드 과정에서 COPY를 한 뒤, 비어있는 로컬 디렉토리에 마운트되면서 사라지는 것 같다.
	- COPY하는 장소를 마운트하는 곳과 다른 곳으로 변경하기
	- 볼륨 마운트를 사용하기.
---
### mariadb 문법 오류
- [ ] 해결 여부
```error
ERROR: 1064  You have an error in your SQL syntax; check the manual that corresponds to your MariaDB server version for the right syntax to use near 'CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci;' at line 1
```
- 문법 공부 겉핥기로
---
### 빌드 어떻게 해야할지 모르겠음
#### 해결(찝찝)
```
docker-compose -f ./srcs/compose.yaml build --no-cache
[+] Building 15.5s (36/38)
[...]
docker compose -f ./srcs/compose.yaml up -d 
[+] Running 2/4
 ⠿ Network mynet      Created                                      0.0s
 ⠿ Container mydb     Created                                      0.0s
 ⠋ Container mynginx  Creating                                     0.0s
 ⠋ Container mywp     Creating                                     0.0s
Error response from daemon: failed to copy files: failed to open target /var/lib/docker/volumes/srcs_wp-vol/_data/default.conf: open /var/lib/docker/volumes/srcs_wp-vol/_data/default.conf: no such file or directory
 ```
`open /var/lib/docker/volumes/srcs_wp-vol/_data/default.conf`
- 이건 도대체 누가 하는 거임? 빌드도 잘 됐는데 왜 이러는지 모르겠음. 
	- 이미 만들어져있는 볼륨에 대해서 참조하는 것이었음.
- 실제적인 문제를 일으킨 원인
	- Nginx의 dockerfile 테스트를 위한 부분이 문제가 되고 있었던 것이었다.
	- `COPY ./tools/ /var/www/html/`
- 내 추측
	- 볼륨이 /var/www/html로 대치 되었고, 빌드 과정에서 nginx/tools를 붙여넣기 함. 이후 볼륨이 연결되면서 그리고 어딘가에서 /var/www/html/default.conf 파일을 참조하려고 하는데 없는 거임. 그래서 이런 오류가 발생한 것 같다.
	- `COPY ./tools/nginx.conf /etc/nginx/nginx.conf` 부분에서 ./tools가 볼륨으로 대체된 것인가 싶기도 하다.
	- 이걸 알려면 도커 컴포즈 소스를 뜯어보아야 할듯.
---
### /home/set.sh line:20 wordpress를  찾지 못함.
#### 해결
- line20인 이유
	- heredoc 내부 문제였음
- 문제의 라인
	- `Use 'docker scan' to run Snyk tests against images to find vulnerabilities and learn how to fix them`
- **쉘 스크립트에서 백틱으로 감싸진 경우 프로그램을 실행하려고 함.**


---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)