---
날짜: 2024-12-27
넘버: 
태그: 프로그래밍
출처: 
aliases:
  - Startup Code
---
### 날짜:  2024-12-27 10:58

### 태그: #프로그래밍 

>[!메모]
>

### 원문
---
# C runtime Environment
- 컴파일러가 만들어주는 코드
![[Pasted image 20250131121841.png]]
- https://developerhelp.microchip.com/xwiki/bin/view/software-tools/c-programming/c-runtime-enviorment/
## 역할
- 애플리케이션 코드가 실행될 수 있도록 한다.
### Allocate a space for a software stack and initilize the stack pointer
- hardware-based return address stack을 가진 8비트 기기에서 소프트웨어 스택은 함수와 주고받는 매개변수 전달에 사용된다.
- 16,비트 32비트 기기에서 소프트웨어 스택이 각 함수 호출과 인터럽트 주소를 반환한다.
### Allocate space for a heap
- A heap is a block of RAM that has been set aside as a sort of scratchpad for your application. C has the ability to dynamically create variables at runtime. This is done in the heap.
### Copy values from Flash into variables declared with initial values
- 초기 값이 있는 형태로 변수가 선언되었을 경우, 프로그램이 실행되기 전에 초기화를 진행해야 한다.
- 초기 값이 플래시 프로그램 메모리 안에 저장되어있을 경우 각 RAM 위치에 할당되어있는 초기화된 변수를 읽어서 복사한다.
### Clear uninitialzed RAM
- Any RAM (file register) not allocated to a specific purpose (variable storage, stack, heap, etc.) is cleared so that it will be in a known state.
### Disable all interrupts
### Call main(), where your application code starts


Runtime environment setup code는 자동으로 애플리케이션과 연결된다.
[[crt0]](.s 또는 .o)
[[TODO]]

### startup code
- 자동으로 startup code를 삽입한다.
	- 작은 어셈블리언어 블럭
```
1. Disable all interrupts. 
2. Copy any initialized data from ROM to RAM. 
3. Zero the uninitialized data area. 
4. Allocate space for and initialize the stack. 
5. Initialize the processor's stack pointer. 
6. Create and initialize the heap. 
7. Execute the constructors and initializers for all global variables (C++ only). 
8. Enable interrupts. 
9. Call main.
```


---
### 생각(파생된 질문/생각)

### 출처
- https://www.e-reading.club/chapter.php/129272/37/michael-barr-programming-embedded-systems-in-c-and-c.html

### 연결 문서 (연결 이유)
- [[Runtime system]]
