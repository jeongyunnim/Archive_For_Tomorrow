---
날짜: '"2023-11-04"'
넘버: 
태그: 프로그래밍/도커
출처: https://docs.docker.com/engine/reference/builder/
aliases:
---
### 날짜  2023-11-04 19:38

### 태그: #프로그래밍/도커 

>[!메모]
>

### 원문
---
# Dockerfile
- docker는 Dockerfile을 읽어 이미지를 자동으로 빌드할 수 있다.
- Dockerfile은 사용자가 명령줄에서 호출하여 이미지를 assemble하기 위해 호출하는 모든 명령이 포함된 문서이다.

## Format
```dockerfile
# Comment

INSTRUCTION argument
```
- INSTRUCTION은 대소문자를 구분하지 않는다. 
- argument와 구분하기 위해 대문자 사용을 권장한다.

- 도커는 Dockerfile의 명령어를 순서대로 실행한다. Dockerfile은 **FROM 명령어로 시작**해야 한다.
- 파서 지시어, 주석 및 전역 범위의 ARG 다음에 올 수 있다.
- `FROM`명령은 빌드 중인 Parent image를 지정한다. FROM 앞에는 하나 이상의 ARG 명령만 올 수 있다. 
- `ARG`명령은 Dockerfile의 FROM 줄에 사용되는 인수를 선언한다.
- 해당 줄이 구문 분석기 지시어가 아니라면 \#으로 시작하는 줄은 주석으로 취급한다.
	- 줄의 다른 위치에 있는 \#마커는 인수로 취급된다.
```dockerfile
# Comment
RUN echo 'we are running some # of cool things'
```
- 주석 줄은 Dockerfile 명령이 실행되기 전에 제거되기 때문에 다음 예제의 주석은 echo 를 실행하지 않는다.
```dockerfile
RUN echo hello \
# comment
world

# same as following instruction
RUN echo hello \
world
```

## Parser directives
### 특징
- 파서 디렉티브는 선택사항이다.
- Dockerfile의 후속 줄이 처리되는 방식에 영향을 준다.
- 빌드에 레이어를 추가하지 않으며 빌드 단계로 표시되지 않는다.
- `# directive=value` 형식으로 작성된다.
- 하나의 디렉티브는 한 번만 사용할 수 있다.
- 주석, 빈 줄, 빌드 명령 뒤에 오는 파서 디렉티브는 유효하지 않기 때문에 맨 위에 있어야 한다.
- 파서 디렉티브는 대소문자를 구분하지 않지만 소문자를 사용하는 것이 관례이다.
- 파서 디렉티브 뒤에는 빈 줄을 포함하는 것이 관례이다.
```dockerfile
# direc \
tive=value
-
# directive=value1
# directive=value2
```
- 알 수 없는 디렉티브가 온 경우 주석으로 처리되기 때문에 아래의 디렉티브 또한 주석으로 처리된다.
```dockerfile
# unknowndirective=value
# knowndirective=value
```
### 지원되는 디렉티브
- `syntax`
- `escape`
### syntax
- [BuildKit](https://docs.docker.com/build/buildkit/) 백엔드를 사용할 때만 사용할 수 있다. 클래식 빌더를 사용할 경우에는 무시된다.
### escape
- escape 지시어는 도커파일에서 문자를 이스케이프하는 데 사용하는 문자를 설정한다.
- default는 `\`이다.
```dockerfile
# escape=\ (backslash)
```
- Window 환경에서 유용
```dockerfile
# escape=` (backtick)`
```
- 이스케이프 문자는 한 문자를 이스케이프하고 새 줄로 이스케이프하는데 모두 사용된다.
	- 도커 파일 명령어를 여러 줄에 걸쳐서 작성할 수 있다.
- 이스케이프 문자가 지정이 되어있더라도, 이스케이프는 줄 끝을 제외하고는 RUN 명령에서 수행되지 않는다.

## Environment replacement
- 환경변수(`ENV`로 선언)은 도커파일에서 해석하는 변수로 사용할 수 있다.
- 변수형 구문을 문자 그대로 명령에 포함하기 위해 escape 문자도 함께 처리된다.
- 환경변수는 Dockerfile 내에서 `$variable_name` 또는 `${variable_name}`으로 선언된다.
	- 중괄호 구문은 `${foo}_var` 처럼 공백 없는 변수 이름의 문제를 해결할 때 유용하다.
- 중괄호 구문은 몇 가지 표준 bash modifiers를 제공한다.
	- `${variable:-word}`: variable이 설정 되어있다면 결과는 그 값이 된다. 설정되어있지 않다면 word가 결과가 된다.
	- `${variable:+word}`: variable이 설정 되어있다면 word가 결과가 된다. 설정 되지 않았다면 빈 문자열이 된다.
	- 모든 경우에서 word는 추가 환경변수를 포함한 모든 문자열이 될 수 있다.
- 적용 예시(escape 문자는 `\`)
```dockerfile
FROM busybox
ENV FOO=/bar
WORKDIR ${FOO}   # WORKDIR /bar
ADD . $FOO       # ADD . /bar  
COPY \$FOO /quux # COPY $FOO /quux
```
- 환경변수는 다음 명령어 목록에서 지원 됨
```
ADD
COPY
ENV
EXPOSE
FROM
LABEL
STOPSIGNAL
USER
VOLUME
WORKDIR
```
### [[.dockerignore file]]
- `.dockerignore`파일을 사용하여 빌드에서 파일 및 디렉토리를 제외할 수 있다.
- 도커 CLI는 도커 데몬으로 context를 전송하기 이전에 `.dockerignore` 파일이 context의 루트 디렉토리에 있는지 찾는다.
- 만약 파일이 존재한다면 해당 파일의 패턴과 일치하는 파일 및 디렉토리를 제외하도록 context를 수정한다.
- 도커 데몬에 필요하지 않은 파일이나 숨겨야하는 파일을 알려주어 ADD나 COPY에서 이미지에 추가되지 않도록 한다.
```dockerfile
# comment
*/temp*
*/*/temp*
temp?
```
- `#`: 주석은 무시된다.
- `*/temp*`현재 루트에 존재하는 모든 디렉토리의 temp를 prefix로 갖는 파일과 디렉토리를 모두 제거한다.
- `temp?`: `?`는 임의의 문자 하나를 가리킨다.
```dockerfile
*.md
!README.md
```
- `!`는 해당 파일은 제외하지 않겠다는 것을 의미한다.

## FROM
```dockerfile
FROM [--platform=<platform>] <image> [AS <name>]
```

```dockerfile
FROM [--platform=<platform>] <image>[:<tag>] [AS <name>]
```

```dockerfile
FROM [--platform=<platform>] <image>[@<digest>] [AS <name>]
```
FROM 명령은 새 빌드 단계를 초기화하고 후속 명령에 대한 [Base image](https://docs.docker.com/glossary/#base-image)를 설정한다.
도커 파일은 FROM 명령으로 시작해야 한다.
특히 공용 저장소로부터 이미지를 가져와서 시작하는 것을 쉽게 만들어준다.
- ARG는 FROM 이전에 사용할 수 있는 유일한 명령어이다.
- FROM은 하나의 Dockerfile 안에 여러 이미지를 생성하거나 의존적인 하나의 빌드 단계를 사용하기위해 여러 번 나타날 수 있다.
	- 각 FROM 명령어는 이전 명령에 의해 만들어진 상태 모두를 지운다.
### ARG와 FROM의 상호작용
```dockerfile
ARG CODE_VERSION=latest
FROM base:${CODE_VERSION}
CMD /code/run-app

FROM extras:${CODE_VERSION}
CMD /code/run-extras
```
FROM은 이전에 발생한 모든 ARG에 선언된 변수를 지원한다.
FROM 이후의 명령에서는 ARG를 사용할 수 없다.
FROM 이전에 만든 변수를 재사용하려면 아래와 같이 작성하라.
```dockerfile
ARG VERSION=latest
FROM busybox:$VERSION
ARG VERSION
RUN echo $VERSION > image_version
```

## RUN
- RUN은 두 가지 형태를 갖는다.
	- `RUN <command>`
		- RUN은 쉘에서 실행된다. (linux의 경우 /bin/sh)
	- `RUN ["excutable", "param1", "param2"]`
- RUN 명령은 현재 이미지 위에 있는 새 레이어에서 모든 명령어를 실행하고 결과를 커밋한다.
- 커밋된 이미지는 Dockerfile의 다음 단계에 사용된다.
- RUN 명령어를 레이어링하고 커밋을 생성하는 것은 저렴하다.
	- 이미지 히스토리 어느 시점에서나 컨테이너를 생성할 수 있다.
	- 소스 제어와 비슷하다.
	- **뭐라는교**
- exec 형식을 사용하면 셸 문자열의 [[munging]]을 방지하고 지정된 셸 실행 파일이 포함되지 않은 기본 이미지를 사용하여 명령을 실행할 수 있다.
- 셸 형식의 기본 셸은 `SHELL` 명령을 사용하여 변경할 수 있다.
- 셸 형식에서 `\`을 사용하여 단일 RUN 명령을 다음 줄로 이을 수 있다.
```dockerfile
RUN /bin/bash -c 'source $HOME/.bashrc && \
echo $HOME'
```
두 명령은 같다.
```dockerfile
RUN /bin/bash -c 'source $HOME/.bashrc && echo $HOME'
```
- 기본 shell이 이외에 다른 셸을 사용하려면 원하는 셸에 실행 형식을 전달하면된다.
```dockerfile
RUN ["/bin/bash", "-c", "echo hello"]
```
- RUN 명령에 대한 캐시는 다음 빌드 중에 자동으로 무효화되지 않는다.
	- `RUN apt-get dist-upgrade -y`같은 명령에 대한 캐시는 다음 빌드 중에 재사용된다.
	- `--no-cache`를 사용하여 무효화할 수 있다.
	- [Dockerfile best practice guide](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)를 참조하라.

## RUN --mount
- 빌드가 액세스할 수 있는 파일 시스템 마운트를 생성할 수 있음.
	- 호스트 파일 시스템 또는 다른 빌드 단계에 바인드 마운트 생성
	- 빌드 시크릿 또는 ssh-agent 소켓 액세스
	- persistent package management 캐시를 사용하여 빌드 속도 향상
- 형태
	- `--mount=[type=<TYPE>][,option=<value>[,option=<value>]...]`

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
