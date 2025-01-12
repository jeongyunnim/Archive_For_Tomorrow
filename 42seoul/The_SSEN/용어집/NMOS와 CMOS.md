---
날짜: 2024-12-30
넘버: 
태그: 
출처: 
aliases:
  - NMOS
  - CMOS
---
### 날짜:  2024-12-30 15:07

### 태그:

>[!메모]
>

### 원문
---
# NMOS와 CMOS
## C.MOS
: complementary metal-oxide-semiconductor
### 명칭
- complementary: 보충적인
- oxide: 산화물
	- 산소와 다른 원소의 화합물
- [[conductor]]: 전도체 < - > [[insulator]]: 절연체 
- COS-MOS라고도 한다.
	- complementary -symmetry metal-oxide-semiconductor
### 특징
- [[집적 회로(IC)]]의 한 종류, [[MPU]]또는 [[SRAM]] 등의 디지털 회로를 구성하는 데 사용된다.
- 전원이 꺼져도 정보를 유지할 수 있다.
### 개요
- P채널과 N채널의 [[FET|MOSFET]]을 [[전원전압]] 간에 직렬로 구성하고 입력은 두 가지 MOSFET 게이트에 같이 연결하고 출력은 두 가지 MOSFET 드레인 사이에 연결한 집적회로의 구조이다.

- 각 MOSFET은 스위치로 간주될 수 있다.
	- 같은 입력신호에 대해 P채널과 N채널이 서로 반대로 동작하기 때문에 [[전원전압]]과 [[접지]] 사이에 기본적으로 흐르는 블리딩 전류가 거의 없어지므로 [[TTL 논리 소자]]에 비해 소비전력이 적은 논리회로를 구성할 수 있고, 부하로 면적을 많이 차지하는 저항 대신 MOSFET을 사용하므로 집적도를 향상시킬 수 있다.

- 게이트 전압에 입력되는 제어 펄스를 1에서 0으로 변경했을 경우 노이즈 없이 이전의 출력을 할 수 있다.
	- 0에서 1로 변경했을 경우 노이즈 없이 입력 신호를 출력할 수 있다.
	- [[TODO]]: **노이즈가 없다는 것이 무슨 의미인가?**

- [[반도체 메모리]]나 [[MCU]]의 논리 [[집적 회로(IC)]]는 대부분 시모스 구조가 되었다.
	- 작은 규모의 전원 회로
	- [[ADC]]
	- [[DAC]]: digital to analog convertor
- 
---
### 생각(파생된 질문/생각)

### 출처
- https://ko.wikipedia.org/wiki/CMOS
- https://web.archive.org/web/20110719014039/http://tams-www.informatik.uni-hamburg.de/applets/cmos/

### 연결 문서 (연결 이유)