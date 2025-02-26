---
날짜: "2025-02-25"
넘버: 
태그: 프로그래밍/임베디드
출처: LIG Nex1 The SSEN Embedded SW School
강사: 홍영기
aliases:
---
### 날짜:  2025-02-25 14:45

### 태그: #프로그래밍/임베디드

>[!메모]
> 

### 원문
---
# GPIO
- 다른 장치를 제어하는 힘을 여기서 배울 것이다.
### 브레드 보드 사용법
- 파란색과 빨간색은 세로로 연결
- 나머지는 가로로 연결
### 점퍼 케이블
- 검정은 그라운드. 빨강은 VCC로 예약해야 한다.
- C언어에서도 인식할 수 있도록 label을 설정해준다.
![[Pasted image 20250225153141.png]]
### 핀의 개념

### 입력 및 출력 모드
- 입력 모드
	- 외부에서 디지털 신호를 받아들이는 모드
- 출력 모드
	- GPIO에서 생성된 디지털 신호를 외부에 전달하는 모드
### F103
- APB2로 연결된다.
- 프로세서를 빼고 전부 주변장치다.
- GPIO도 주변 장치 중 하나이다.
### STM32의 GPIO 아키텍처
- GPIO 레지스터를 이용해야 한다.
- GPIO Register
	- GPIOx_ODR, GPIOx_IDR
- **32비트(워드)** 로만 액세스 해야 한다.
	- 바이트 8비트
	- 하프워드 16비트
- 데이터 시트
	- 이해가 되든 말든 읽어본다.
		- 몇 번을 읽어도 건질 수 있는 게 없다.
	- 데이터 시트를 읽지 않고 반도체 제조사(stm32)의 샘플 소스를 본다.
		- github에 tutorial, sample 등을 검색해본다.
		- 소스코드를 쫓아가다보면 SFR을 제어하는 것을 발견하게 된다.
		- 하드웨어 레지스터들의 비트를 제어
		- 레지스터 이름을 데이터 시트에서 찾는다.
		- 읽다보면 모르는 게 나온다.
		- 그림이 나올 때까지 다시 검색해서 그림과 설명을 통해 이해를 노력하기
		- 위로 스크롤 하여 찾고 있는 단어를 포함하고 있는 섹션을 읽어보기
	- 조각조각을 다 이해하기
		- 그림, 설명, 코드를 종횡무진하며 최대한 부분을 이해하도록 노력한다.
		- 점점 밝아진다.
- 비행기 조종석을 보라
	- 수많은 계기판.. 중요한 것들만 체크할 것이다.
- STM32의 GPIO는 어렵다.
	- 하지만, **본질적인 기능**이 무엇인가에 집중하자.
	- 혼자 공부하면 어떤 것이 핵심이고 주변인지 모르기 때문이다.
### LED가 켜지는 순서
- 프로그램이 ODR의 GPIO의 핀과 연결된 비트 x번을 SET한다.
- 전자회로에서 HIGH 신호가 가도록 세팅되어 있다.
- 전류가 높은 곳에서 낮은 곳에서 흐르면서 LED에도 전류가 제공이 된다.'

- 슈미츠 트리거
	- 외부 신호가 너무 강할 때, 노이즈로 취급을한다.
- 프로텍션 다이오드
	- 외부에서 들어오는 전기 신호가 보드를 파괴하려고 할 때, 방어하기 위함
- push/pull
- open drain
	- pull up 저항을 설정해주어야한다.
### Alternate functions
- 제 3의 기능
	- GPIO가 아닌 다른 기능으로 선택할 수 있다.
- 포트비트가 Alternate functions로 설정되어있는 경우 출력 레지스터 연결을 끊고 핀을 온칩 주변 장치의 출력 신호에 연결시킨다.
- [[MUX]]로 구성되어 있다.
	- PIN MUX라고 부른다.
![[Pasted image 20250226092821.png]]
### automic set / reset
- 나중에
### BSRR vs ODR
- 나중에
### GPIO 레지스터의 종류
- 제어해야 할 레지스터가 많지 않다.
- 이 중에서도 일부의 레지스터만 제어하면 된다.
	- 어떻게 찾아내는가를 알아야한다.
- **configuration register**
- **input/output register**
- bit set/reset register
- configuration lock register
### CMSIS, HAL, LL
- 주변 장치들은 STM32가 가지고 있는 [[반도체 IP(Intellectual Property)|IP]]이다.
	- IP는 모든 제조사가 공유한다.
- 컴파일러 회사(벤더)이 컴파일러를 제공하려면, 수백개의 칩의 설계를 감당했어야 했다.
	- ARM은 표준화를 주도했다.
		- FPU, NVIC, ETM, MPU가 공통이다.
- CMSIS
	- Cortex Microcontroller Software Interface Standard
	- ARM에서 제공하는 소프트웨어 인터페이스 표준
	- Intel이 지배하고 있었던 칩 시장을 가져올 수 있었던 힘
	- `Drivers/CMSIS/Include`의 헤더파일을 보면, ARM이 제공하고 있는 것을 확인할 수 있다.
- HAL
	- 하드웨어의 소프트웨어적 제어를 편하게 사용할 수 있도록 만든 라이브러리
- LL
	- Low Layer Drivers
	- STM에서 개발한 하드웨어 추상화 라이브러리
	- 이식성이 HAL만큼 좋지 않다.

### SFR 제어 실습
- 단순 GPIO를 제어하는 방법을 배우는 것이 아니다.
- 프로세스를 기억하자.
	- 회로 분석을 먼저 해야한다.
		- schematic
- LED -> 다이오드의 특성을 따라간다.
	- 애노드 -> 캐서드
	- 화살표 방향으로만 전류가 흐른다.
	- 왼쪽: HIGH -> 오른쪽: LOW
- 회로도
	- 같은 이름끼리 연결되는 것
	- PDF 상에서 해당 이름으로 검색해서 연결부를 확인한다.
![[Pasted image 20250226101524.png]]
- 메모장을 열어 기록
	- PG13: 메모리 켜려면 **HIGH**
- 데이터 시트에서 검색
	- 있으면 좋고 없으면 그만
	- 없을 경우 정밀 검색, 숫자를 지운다.
	- introduction을 읽고 -> 마지막의 register 항목을 살펴본다.
	- offset 주소를 보자
	- [ ] 레지스터는 32비트 -> int/long: ARM에서는 상관 없다.
		- int의 사이즈는 16/32 시스템을 따라간다.
		- long의 사이즈는 무조건 32
		- ARM은 16 비트 시스템이 없다. 그래서 상관 없는 것.
![[Excalidraw/LIG Nex1 임베디드.md#^group=eWgJKG-Z4bClg_nQQwrVE]]
- 프로그램으로 옮긴다.
	- 레지스터 변수를 선언하는 법
		- unsigned int
		- pointer
		- **volatile**
- 레지스터 맵핑
```c
volatile unsigned int *rGPIOG_ODR = (unsigned int*)(0x40021800 + 0x14);
```
- 이식성은 없다.
	- 만약 다른 장치에서 동작하도록 바꾸려면, 해당 핀 번호와 주소 등을 모두 다시 작성해주어야 한다.
### LL 제어 실습
- 프로젝트 생성 후 ioc 파일에서 LL사용을 설정해주어야 한다.
![[Pasted image 20250226110807.png]]
```c
LL_GPIO_TogglePin(LD3_GPIO_Port, LD3_Pin);
```
### 어셈블리 제어 실습

```
MY_LL_GPIO_TogglePinASM:
	push {lr}
	@ volatile unsigned long *rGPIOG_ODR= (volatile unsigned long*)0x40021814;
	@ *rGPIOG_ODR = *rGPIOG_ODR ^ (1<<13); // LED 'TOGGLE'
	@ return 0;
	ldr r0,=rGPIOG_ODR
	ldr r1,[r0]
	eor r1,r1,#(1<<13)
	str r1,[r0]
	pop {pc}

```
- lr을 push하고, pc를 pop하여 함수의 기본 형태를 만든다.
```
MY_LL_GPIO_TogglePinASM:
	push {lr}
	...
	pop {pc}

```
- 값을 읽어와서 exclusive or 연산하여 다시 그 값을 덮어쓰도록 설정
```
MY_LL_GPIO_TogglePinASM:
	push {lr}
	ldr r1,=0x40021814 // r1 = 0x40021814
	ldr r0,[r1] // r0 = ODR의 값
	eor r0,#(1<<13)
	str r0,[r1]
	pop {pc}
```
### BSRR 제어 실습
![[Excalidraw/LIG Nex1 임베디드.md#^group=x0cnsm8fVKCKvPNU4ClLv]]
```
volatile unsigned long *rGPIOG_BSRR= (volatile unsigned long*)0x40021818;
volatile unsigned long *rGPIOG_ODR= (volatile unsigned long*)0x40021814;
if(*rGPIOG_ODR & (1<<13)){
	*rGPIOG_BSRR = (1<<(13+16)); // OFF
}
else {
	*rGPIOG_BSRR = (1<<(13+0)); // ON
}
```
### GPIO port mode register
- ouput모드 세팅 등은 이미 설정이 되어있다.
	- `MX_GPIO_Init()`
- 레지스터를 어떻게 제어하고 있는지 들여다봐야 한다.
	- breakpoint를 HAL_Init(), GPIO_Init(), CRC_Init()에 건다.
	- 굳이 소스코드를 분석하지 않고도 어떤 비트가 수정되는지 알 수 있다.
![[Pasted image 20250226113224.png]]
![[Pasted image 20250226113246.png]]
![[Pasted image 20250226113311.png]]
- 변경되는 값을 손쉽게 알아낼 수 있다.
	- 이 값들만 데이터시트에서 찾아본다.
#### MODER

![[Excalidraw/LIG Nex1 임베디드.md#^group=CnpH9riNXXLN9hDPQ8wQV]]
- direction 세팅, odr 세팅해주면 바로 제어가 가능하다.
	- 만약 몰랐다면 데이터시트 열심히 읽으면서 시간을 많이 들였을 것이다.

#### OSPEEDR
- GPIO의 부가기능
	- 신호의 주기가 달라지거나 하는 것은 아니다.
	- 전자파가 많이 나오거나 적게나오게 할 수 있다.
	- 열심히 읽어보고 제어 해봤지만, 쓸데 없더라.
	- 쓰지도 않을 기능..
```c
  /*Configure GPIO pins : RDX_Pin WRX_DCX_Pin EXLED_Pin */
  GPIO_InitStruct.Pin = RDX_Pin|WRX_DCX_Pin|EXLED_Pin;
  GPIO_InitStruct.Mode = GPIO_MODE_OUTPUT_PP;
  GPIO_InitStruct.Pull = GPIO_NOPULL;
  GPIO_InitStruct.Speed = GPIO_SPEED_FREQ_LOW;
  HAL_GPIO_Init(GPIOD, &GPIO_InitStruct);
```
- 핵심을 파악 한 뒤에 시간 남으면 이런 것들을 배워가며 확장하라.
### 내부 버튼 실습
- 회로분석
	- PA0, 버튼을 눌렀을 때 HIGH 전압
- 프로젝트는 거창할 필요가 없다.
	- 프로젝트에 큰 의미를 안 둔다.
	- [ ] 기본기가 중요하다. 빠져나갈 수 있는 구멍을 안 준다. 
		- 포인터를 알아요? -> 끝
		- 커널 컴파일 해봤어요? -> 안해봤어요 다음 질문
		- 답변이 너무 정형화되어 있으면 실제 지식이라기 보다는 암기라는 것을 들킬 수 있다.
		- 어떤 도전으로 어떤 지식을 쌓는다를 목표로.
- 아래의 템플릿을 만들 수 있다.
```c
volatile unsigned int* rGPIOA_IDR = (unsigned int*)
```
### 외부 버튼 실습
- 네 개의 다리
```c
// (1)
*rGPIOC_PUPDR = (*rGPIOC_PUPDR & ~(3<<10) | (1 << 10));// (1)
// (2)
*rGPIOC_PUPDR = (*rGPIOC_PUPDR & ~(1<<11) | (1 << 10));// (2)
// (3)
*rGPIOC_PUPDR = *rGPIOC_PUPDR & ~(1 << 11);
*rGPIOC_PUPDR = *rGPIOC_PUPDR | (1 << 10));
```
- 여태까지는 1비트를 제어했다.
	- **커플링된 비트는 묶어서 처리**해야 한다.
	- 1번이 옳다.
	- 11번 비트를 지울 때, 00이나 01의 값을 가질 수 있다.
		- 방사선을 차단하는 기능이었다. -> 치명적일 수 있다.
- 
---
### 생각(파생된 질문/생각)

### 출처
- LIG Nex1 The SSEN Embedded SW School

### 연결 문서 (연결 이유)
