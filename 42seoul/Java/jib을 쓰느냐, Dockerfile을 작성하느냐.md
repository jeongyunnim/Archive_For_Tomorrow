---
날짜: 2024-07-22
넘버: 
태그: 프로그래밍/도커
출처: 
aliases:
---
### 날짜:  2024-07-22 15:17

### 태그: #프로그래밍/도커 

>[!메모]
>

### 원문
---
# jib을 쓰느냐, Dockerfile을 작성하느냐

- jib은 java의 gradle maven에서 사용가능한 docker image 빌드 툴이다.
- 각 서비스의 dockerfile을 임의로 작성하는 것은 너무나 번거로운 일이기 때문에 jib을 사용하는 것이 서비스 배포의 pipeline을 획기적으로 줄일 수 있다고 생각했다.
### jib을 통한 이미지 빌드에서 문제가 발생했다. 
- m1 칩 에서 동작하도록 하는 것은 추가적인 설정이 필요했다.
- 베이스 이미지와 이미지 이름, 이미지의 태그를 설정해주는 것이 설정파일의 복잡성을 늘리는 일은 아닌가 우려된다.
- 기본 패키지에 health체크에 필요한 바이너리 파일(curl)이 없다.

```xml
<build>
	<plugins>
		<plugin>
			<groupId>com.google.cloud.tools</groupId>
			<artifactId>jib-maven-plugin</artifactId>
			<version>3.4.3</version>
			<configuration>
				<from>
					<platforms>
						<platform>
							<architecture>amd64</architecture>
							<os>linux</os>
						</platform>
						<platform>
							<architecture>arm64</architecture>
							<os>linux</os>
						</platform>
					</platforms>
				</from>
				<to>
					<image>jeongyun7521/${project.artifactId}:s6</image>
				</to>
			</configuration>
		</plugin>
	</plugins>
</build>
```

영문을 모르겠다.
동영상 예제에서는 curl을 잘만 사용하는데, 나만 안 되는 건지.
- 진행은 해야 하기 때문에 아래와 같이 진행했다.
- jar 빌드
```sh
$> ./gradlew build
```
- docker 파일 작성
```dockerfile
FROM openjdk:17-jdk-slim  
  
MAINTAINER jeseo  
  
COPY build/libs/configserver-0.0.1-SNAPSHOT.jar configserver-0.0.1-SNAPSHOT.jar  
  
RUN apt-get update && apt-get upgrade -y  
RUN apt-get install curl -y  
  
ENTRYPOINT ["java", "-jar", "configserver-0.0.1-SNAPSHOT.jar"]
```
- docker image 빌드
```sh
$> docker build . -t jeongyun7521/configserver:s6
```
![[Pasted image 20240722163832.png]]

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
\