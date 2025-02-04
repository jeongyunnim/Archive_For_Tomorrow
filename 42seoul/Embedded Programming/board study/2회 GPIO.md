---
날짜: "2025-02-03"
넘버: 
태그: 프로그래밍/임베디드
출처: 
aliases:
---
### 날짜:  2025-02-03 18:18

### 태그: #프로그래밍/임베디드

>[!메모]
>

### 원문
---
# 2회 GPIO
### Memory mapped([[MMIO]])
- 프로세서를 중심으로 다양한 peripheral들이 버스로 연결된다.
- 메모리를 포함한 다양한 페리페럴을 제어하기 위해 memory mapped 개념을 사용한다.
![[Pasted image 20250204134210.png]]
![[Pasted image 20250204134238.png]]
- 메모리와 페리페럴의 주소 공간을 분리하지 않고 하나의 메모리 공간 처럼 취급한다.
- 프로세서는 GPIO를 제어하기 위해 해당하는 레지스터를 메모리처럼 **주소로 접근**하여 값을 읽거나 쓴다.
![[Pasted image 20250204135935.png]]
- Section 9.5로 이동하면 각 GPIOx(x = A~G)포트에 관련된 레지스터를 볼 수 있다.
- offset이 4byte 단위인 이유
	- 레지스터가 32bit이기 때문이다. 
- 레지스터에 접근하기위해서는 baseaddress와 offset을 사용한다.
```c
// 레지스터 접근 주소 : base address + offset
// Ex1) GPIOA의 IDR에서 값을 읽을 때, 0x40010800(GPIOA base addr) + 0x08(offset)
short a = *((unsigned short*)0x40010808);
// Ex2) GPIOA의 ODR에 0xFFFF를 쓸 때
*((volatile unsigned short*)0x4001080C) |= 0xFFFF;
```

### GPIO
- [[GPIO|General-purpose I/O]]
	- 입력이나 출력을 포함한 동작이 런타임 시에 사용자에 의해 제어될 수 있는 집적회로나 전기 화로 기판의 디지털 신호 핀
	- 버튼(input), LED(output)을 사용할 수 있도록 지원해주는 peripheral
#### 입력
- I/O핀으로 입력이 들어오면 input driver를 거쳐 IDR에 저장된다.
	- input driver
		- bouncing 을 막아주는 회로
	- [[pull-up pull-down 저항]]을 통해 확실한 1과 0을 얻어낸다.
		- pull-up pull-down 자체가 실제로 값을 가지지 않는다.
#### 출력
- ODR에 출력하고자 하는 데이터를 쓰면 output pin으로 출력할 수 있다.
- output driver에서 출력 방식을 설정할 수 있다.

### 인터럽트
- 인터럽트의 종류
	- 내부 인터럽트
	- 외부 인터럽트([[EXTI]]. External Interrupt)
- 프로세서는 프로세서 내의 IP인 [[NVIC]]에서 우선순위를 비롯한 정보를 반영하여 모든 인터럽트를 처리한다.

> [!외부 인터럽트의 처리 과정]
> ![[Pasted image 20250204174905.png]]
> 1. 인터럽트 발생
> 2. EXTI에서 인터럽트 발생 감지
> 3. EXTI가 플래그(PR, pending register) set
> 4. NVIC이 인터럽트 활성화하고 우선순위를 확인하여 [[ISR]]분기
> 5. ISR 수행하고 플래그 clear
> 6. 복귀


### 실습
- CubeIDE에서 STM32 project 생성
	- F103RB 
- GPIO 13번 핀
![[Pasted image 20250203184144.png]]
- PA 이름의 정체
#### LED 제어하기
- PC-TAMPER-RTC
	- falling edge
- NVIC
	- 15번 핀
- init
	- 전원이 켜지고 빠르게 동작해야 하는 경우
	- 노말 스테이터스로 진입해야 인터럽트 처리가 가능하다.
- 인터럽트
	- startup code `.word 인터럽트 핸들러`
		- NVIC가 이쪽으로 가라고 지정이 되어있다..
	- 4바이트 주솟값을 처음에 모조리 초기화 한다.
	- 레지스터에 플래그를 올려준다.

- 디폴트 핸들러가 weak로 제공된다. 애플리케이션 함수안에 재정의를 해야 한다.
```c
__weak void HAL_GPIO_EXTI_Callback(uint16_t GPIO_Pin)
{
  /* Prevent unused argument(s) compilation warning */
  UNUSED(GPIO_Pin);
  /* NOTE: This function Should not be modified, when the callback is needed,
           the HAL_GPIO_EXTI_Callback could be implemented in the user file
   */
}
```

```c
void HAL_GPIO_EXTI_Callback(uint16_t GPIO_Pin)
{
  /* Prevent unused argument(s) compilation warning */
*((unsigned int*)0x4001080C) = *((unsigned int*)0x4001080C) ^ (1 << 5);
  UNUSED(GPIO_Pin);
  /* NOTE: This function Should not be modified, when the callback is needed,
           the HAL_GPIO_EXTI_Callback could be implemented in the user file
   */
}
```
### CPU는 실제 인터럽트를 어떻게 찾아가는가?
- NVIC에 인터럽트 신호가 들어온 칩에 해당하는 인터럽트 핸들러를 호출
	- 인터럽트 테이블을 가지고 있다.
	- 활성화된 인터럽트에 해당하는 로직을 실행한다.
	- [ ] CPU가 인터럽트를 찾아가는 과정 
```c
static int pr_reg = 0;

void HAL_GPIO_EXTI_Callback(uint16_t GPIO_Pin)
{
  pr_reg = *((unsigned int*)0x40010414);
}
```


---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
