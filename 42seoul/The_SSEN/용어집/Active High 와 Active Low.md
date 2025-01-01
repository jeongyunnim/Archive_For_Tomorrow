---
날짜: 2025-01-01
넘버: 
태그: 전기
출처: 
aliases:
---
### 날짜:  2025-01-01 19:17

### 태그: #전기

>[!메모]
>

### 원문
---
# Active High 와 Active Low
### Active Low의 표현
- 상부에 줄을 그어서 표현한다.
```
-----
reset
```
## 동작의 차이
### Active High(AH)
- 입력값이 high일 때 동작
![[Pasted image 20250101192022.png]]
io 핀의 출력이 high일 때 LE에 빛이 들어온다.
### Active Low(AL)
 입력값이 low일 때 동작
 ![[Pasted image 20250101192227.png]]

### Floating 상태
- 입력되는 저항이 0도 아니고 1도 아닌 상태
- 예상치 못한 결과를 초래할 수 있다.
- 동작방식이 AL, AH인지에 따라 [[pullup pulldown 저항]]을 걸어준다.

---
### 생각(파생된 질문/생각)

### 출처
- https://boradol0902.tistory.com/23

### 연결 문서 (연결 이유)
- [[Floating 상태]]
- [[pullup pulldown 저항]]