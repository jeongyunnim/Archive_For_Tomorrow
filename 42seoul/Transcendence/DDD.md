---
날짜: 2024-02-21
넘버: 
태그: 프로그래밍/설계
출처: https://happycloud-lee.tistory.com/94
aliases:
---
### 날짜  2024-02-21 23:18

### 태그:

>[!메모]
>

### 원문
---
# DDD
: Domain Driven Design
![[Pasted image 20240221234836.png]]
## DDD 요약
- 비즈니스 도메인 별로 나누어 설계하는 방식
- 핵심 목표
	- Loosly coupling(의존성 최소화)
	- High cohesion(응집성 최대화)
- 설계 방식
	- Strategic Design(개념 설계)
	- Tactical Design(구체적 설계)
### Strategic Design
- 비즈니스 도메인의 상황(Context)에 맞게 설계하는 것.
- Context를 Event storming으로 공유하고 비즈니스 목적 별로 서비스들을 그룹화한다.
- Bounded Context
	- 사용자, 프로세스, 정책/규정 등을 고유한 비즈니스 목적별로 그룹화.
	- 최소 1개 이상의 MS로 구성된다.
- Domain Model
	- 비즈니스 도메인의 서비스를 추상화한 설계도.
- Context map
	- Bounded Context간의 관계를 나타낸 다이어그램
- Ubiquitous Language
	- 현업, 개발자, 디자이너 등이 동일한 의미로 이해하는 언어
	- 공통언어를 정의하고 사용하여 중복되는 어휘를 구분
- 도메인 모델을 결과물로 얻을 수 있다.
![[Excalidraw/ft_transcendence.excalidraw.md#^group=MkciipDPDE4ZHljVToDEV]]
![[Excalidraw/ft_transcendence.excalidraw.md#^group=mX0yC4ak9P6URYK9eBGC8]]
### Event storming
```
1. Domain Event 정의
2. Tell the story
3. 프로세스 그룹핑
4. Command 정의
5. Trigger 정의
6. Aggregate 정의
7. Bounded Context 정의
8. Context Map 작성
```



---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
