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

### GPIO
- input driver
	- bouncing 을 막아주는 회로
- pull-up / pull-down
	- 실제로 값을 가지지 않는다.
	- 0과 1을 확실하게 만들어주기 위한 회로
### 실습
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
