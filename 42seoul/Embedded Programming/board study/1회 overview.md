---
날짜: 2025-01-23
넘버: 
태그: 프로그래밍/임베디드
출처: 
aliases:
---
### 날짜:  2025-01-23 18:28

### 태그: #프로그래밍/임베디드

>[!메모]
>

### 원문
---
# 1회 overview
## 개발 도구 설치
- STM32CubeIDE
	- STM32의 통합 개발 환경
	- Peripheral 설정과 코드를 생성해준다.
		- CubeMX
	- 코드 컴파일 및 디버그
	- CPU core register, memory, peripheral register 뷰어 제공
- STM32CubeMX 
	- peripheral 설정 및 코드 생성
	- middleware stack 및 library 지원
	- 다른 코드 generator나 IDE 사용 시 CubeMX로 MCU를 설정하고 Application을 개발한다.
- STM32CubeProgrammer
	- Degug Interface(JTAG, SWD)와 부트로더 인터페이스 (UART, USB DFU, I2C, SPI, CAN)을 통해 메모리를 읽고 쓰고 검증할 수 있는 환경을 제공한다.
	- STM32 내부 메모리(Flash, PRM, OTP)와 외부 메모리 프로그래밍
- Hercules
	- 시리얼 통신 모니터링
## MCU
Micro Controller Unit
- Embedded 제어를 목적으로 제조된 One Chip U-computer
- 프로세서 + 버스 + peripheral
	- peripheral: GPIO, UART, I2C, SPI, Timer, ADC, Ethernet, USB 등
### PC와 비교

|       | PC                 | Embedded System      |
| ----- | ------------------ | -------------------- |
| 목적    | 범용성, 다양한 작업        | 특화, 특정 기능            |
| 하드웨어  | 고성능, 확장성, 범용 인터페이스 | 저성능, 저전력, 전용 하드웨어    |
| 소프트웨어 | OS                 | Bare-metal, [[RTOS]] |
- Bare-metal: 하드웨어를 직접 다룬다.

|      | 파일             | 위치     | PC 프로그래밍 | Embedded Controller 프로그래밍 |
| ---- | -------------- | ------ | -------- | ------------------------- |
| 프로그램 | `.c`           | 파일 위치  | DRAM     | DRAM(PC)                  |
| 컴파일러 | `.o`           | 파일 위치  | DRAM     | DRAM(PC)                  |
| 링커   | `.exe`, `.elf` | 파일 위치  | DRAM     | DRAM(PC)<br>-> Flash(EC)  |
|      |                | CPU 위치 | PC       | EC                        |
|      |                | 제어 대상  | PC       | EC                        |

- Native Compiler
	- 컴파일러가 실행되는 시스템과 바이너리 파일이 실행되는 프로그램이 **일치**
- Cross Compiler
	- 컴파일러가 실행되는 시스템과 바이너리 파일이 실행되는 프로그램이 **불일치**
## NUCLEO-F103RB

![[Pasted image 20250128210214.png]]
![[Pasted image 20250128210219.png]]
![[Pasted image 20250128210227.png]]
- Arduino Connector 지원
	- 아두이노 쉴드로 나온 제품을 사용할 수 있다.
	- 이더넷, 블루투스 쉴드 등 손쉽게 제품을 겹쳐서 연결하여 기능을 확장할 수 있다.
- USER LED, push button이 내장되어있다.
	- 검정 버튼, MCU
	- 파란 버튼, 스위치
- [[ST Link]] 내장
- X2 크리스탈 LSE 발진기 내장
![[Pasted image 20250128211557.png]]
- AHB: Advanced High-performance Bus
- APB: Advanced Peripheral Bus



- 오실레이터

- 수컷 핀은 어떻게 연결되는지
- 통신
	- SPI
	- UART
	- I2C
	- USB
	- CAN
- 소비전력 측정
- ADC
![[Pasted image 20250123190708.png]]
- 오른쪽 클럭이 더 낮다.
- 오실레이터
	- 클럭을 만들어준다.
	- 좀더 안정적인 클럭
- Bus Matrix
	- 다른 클럭의 데이터의 동기화를 담당한다.
- 클럭이 다른데 어떻게 가능한가?
	- 분리되어서 동작할 수도 있다.
![[Pasted image 20250123192950.png]]
![[Pasted image 20250123194035.png]]
- [[DMA]]
	- 어떤 메모리에서 어떤 메모리로 복사할지
	- 주변장치에서 통신 정보를 받아서 올릴 때?
- [[The_SSEN/0.1 용어집/GPIO]]
- [[NVIC]]
	- 인터럽트 설정
	- 동시에 발생 시, 우선순위 설정 등
- [[RCC]]
- [[WWDG]]
- [[HAL 라이브러리]]



---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
