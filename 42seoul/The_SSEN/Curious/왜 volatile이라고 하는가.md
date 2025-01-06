---
날짜: 2025-01-05
넘버: 
태그: 프로그래밍/임베디드
출처: https://www.jaenung.net/tree/1214?srsltid=AfmBOopje-naPtX3CQ2isJGi46XrJFz7z-kLAMjPdI1Ja75NJyjl9k3d
aliases:
  - volatile
---
### 날짜:  2025-01-05 21:56

### 태그: #프로그래밍/임베디드 

>[!메모]
>

### 원문
---
# 왜 volatile이라고 하는가?
- volatile 키워드는 변수를 선언할 때 선언하는 **qualifier**이다.
- volatile은 **휘발성의**라는 의미를 가진다.
- 따라서 이 값은 쉽게 변하므로, 컴파일러에게 해당 변수의 값을 **항상** 메모리에서 가져오도록 강제하는 키워드이다.

### volatile의 기능
- 최적화 방지
- 메모리 가시성
- 순서 보장
### 최적화 방지
- 루프 내에서 변수 값이 변하지 않는다면 그 값을 레지스터에 캐시하여 메모리 접근을 줄인다.
```c
volatile int sensor_value;

while (1) {
	if (sensor_value > threshold) {
		// do somthing
	}
}
```
- volatile로 선언되어있지 않았다면 한 번만 읽고 그 값을 레지스터에 저장하여 계속 그 값을 읽어오랴ㅕ고 할 것이다.
### 메모리 가시성
- 현대의 컴퓨터 아키텍쳐에서는 여러 단계의 캐시 메모리를 사용한다.
	- [[캐시]]
- CPU 코어마다 별도의 캐시를 가지고 있기 때문에 멀티코어 환경에서는 각 코어가 같은 메모리 주소에 대해 다른 값을 가질 수 있다.
![[Excalidraw/LIG Nex1_embedded_C.md#^group=KSV0CuyWiCgCWZkxlptmM]]
- volatile 변수는 캐시를 거치지 않고 메인 메모리와 상호작용한다.
	- 모든 스레드가 항상 최신 값을 볼 수 있게 해준다.
### 순서 보장
- 컴파일러와 CPU는 성능 향상을 위해 명령어의 순서를 재배치하는 경우가 있다.
- 특정 순서로 레지스터에 값을 쓰는 것이 필요한 경우 volatile을 사용해야 한다.
```c
volatile uint_t* control_register = (uint8_t*)0x1234;
volatile uint_t* data_register = (uint8_t*)0x1235;

*control_register = 0x01; // 제어 레지스터 설정
*data_register = 0x42;    // 데이터 쓰기
```
- 위의 경우 control_register에 대한 쓰기가 data_register에 대한 쓰기보다 먼저 실행됨을 보장한다.

## 용례
### 인터럽트 서비스 루틴([[ISR]])
- [[ISR]]은 하드웨어 인터럽트가 발생했을 때 실행되는 특별한 함수이다.
- 메인 프로그램과 ISR이 공유하는 변수는 일반적으로 volatile로 선언해야 한다.
```c
volatile int flag = 0;

void interrupt_handler() {
	flag = 1;
}

int main() {
	while (!flag) {
		// wait
	}
	// interrupt 이후 실행될 코드
	return 0;
}
```
- 위에서 flag가 volatile로 선언되지 않았다면 컴파일러는 while loop를 무한루프로 최적화할 수 있다.
- volatile로 선언했기 때문에 flag의 값을 매번 메모리에서 읽어와 인터럽트 핸들러에 의한 변경을 즉시 감지할 수 있다.
### 메모리 맵 입출력(I/O, [[MMIO]])
- [[MMIO]]
- 많은 임베디드 시스템에서는 특정 메모리 주소를 통해 하드웨어 장치와 통신한다.
	- volatile의 사용이 필수적이다.
```c
volatile uint32_t* const UART_DATA_REG = (uint32_t*)0x40000000;
volatile uint32_t* const UART_STATUS_REG = (uint32_t*)0x40000004;

void send_byte(char c) {
	while (!(*UART_STATUS_REG & 0x01)) {
		// UART가 준비될 때까지 대기
	}
	*UART_DATA_REG = c;
}
```

- [[UART]]가 준비될 때까지 기다릴 수 있도록 volatile을 선언해준다.
- volatile로 선언하지 않는다면 컴파일러는 레지스터 값이 변하지 않는다고 생각하여 잘못된 최적화를 진행할 수 있다.

## 주의
- 과도한 사용 시 성능을 저하시킬 수 있음.
- 원자성 보장되지 않음.
	- 멀티스레드 환경에서 데이터 레이스가 일어날 수 있다.
	- 추가적인 동기화 매커니즘이 필요하다.
---
### 생각(파생된 질문/생각)

### 출처
- [재능넷](https://www.jaenung.net/tree/1214?srsltid=AfmBOopje-naPtX3CQ2isJGi46XrJFz7z-kLAMjPdI1Ja75NJyjl9k3d)

### 연결 문서 (연결 이유)
- [[디바운싱]]
