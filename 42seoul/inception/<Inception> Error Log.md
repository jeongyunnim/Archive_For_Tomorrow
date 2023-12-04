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
- 빌드 과정에서 COPY를 한 뒤, 비어있는 로컬 디렉토리에 마운트되면서 사라지는 것 같다.
	- COPY하는 장소를 마운트하는 곳과 다른 곳으로 변경하기
	- 볼륨 마운트를 사용하기.
### mariadb 문법 오류
```error
ERROR: 1064  You have an error in your SQL syntax; check the manual that corresponds to your MariaDB server version for the right syntax to use near 'CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci;' at line 1
```

### 도커 컴포즈 마운트 실패
```
Error response from daemon: failed to mount local volume: mount ./requirements/wordpress/tools/volume_wp/wordpress:/var/lib/docker/volumes/srcs_wp-vol/_data, flags: 0x1000: no such file or directory
make[1]: *** [all] Error 1
make: *** [re] Error 2
```
- 마운트 실패

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)