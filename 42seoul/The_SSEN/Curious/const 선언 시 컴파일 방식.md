---
날짜: 2025-01-13
넘버: 
태그: 프로그래밍
출처: chatGPT,
aliases:
---
### 날짜:  2025-01-13 00:57

### 태그:

>[!메모]
>

### 원문
---
# const 선언 시 컴파일 방식
- CV-qualifiers
	- https://en.cppreference.com/w/cpp/language/cv
	- const and volatile type qualifiers
- const와 volatile은 타입 수정자이다.
### 컴파일러 파싱 규칙
- 우측에서 좌측 방향으로 읽는다. `<-`
- `const`가 오면 타입 수정자로 해석한다.
- `const`가 앞에 오면 뒤의 기본 자료형을 const로 수정한다.
	- `int const x = 10;`
```c
const int x = 10; // x는 상수화된 int 
int const x = 10; // x는 상수화된 int (동일한 의미)
```
#### **컴파일러 해석**
1. `const int x = 10;`
    - 컴파일러는 `const`를 보고, 뒤의 `int` 타입을 상수화합니다.
2. `int const x = 10;`
    - 컴파일러는 `int`를 읽고, 뒤의 `const`를 상수화 타입으로 추가합니다.

---
### 생각(파생된 질문/생각)

### 출처

### 연결 문서 (연결 이유)
