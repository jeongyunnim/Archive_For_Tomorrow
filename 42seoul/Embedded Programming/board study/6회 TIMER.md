---
날짜: "2025-02-17"
넘버: 
태그: 프로그래밍/임베디드
출처: 
aliases:
---
### 날짜:  2025-02-17 18:25

### 태그: #프로그래밍/임베디드

>[!메모]
>

### 원문
---
# 7회 TIMER
## 타이머란 무엇인가
- 시간 및 이벤트 관리를 위해 사용하는 하드웨어 모듈
- PWM: 1과 0 
	- 관성 때문에 평균 값을 사용한다.
- Advanced Timer: TIM1, TIM8
	- PWM이 더 많거나, 브레이크, 컴플리멘터리 출력 지원
- 우리가 쓰는 보드는 1-4까지 있다.
## Timer 동작 원리
- Clock 입력
	- 보통 APB 버스 클럭을 받아서 동작(APB1 = 72MHz)

## 추가 설명
- HAL_TICK
	- 최대 1ms
	- 인터럽트에 의해 
- SYSTICK

- 버스는 클럭과 언제나 함께 동작한다.

![[Excalidraw/Board Study.md#^group=lwoEKOSb]]

- advanced timer의 채널: ARR은 하나로, CCR을 4개로 나누어 4개의 PWM을 생성할 수 있다.

- 하나의 master와 5개의 slave timer들로 고정밀의 시간 간격을 생성할 수 있는 High Resolution timer와 low power timer가 있다.
	- [ ] RTOS랑 같이 물릴 때는 HAL의 timer를 basic 타이머(6, 7번으로 설정한다.)
![[Pasted image 20250212085656.png]]

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
