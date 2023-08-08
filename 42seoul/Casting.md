----
- Casting
1. 값
    
    - 두 숫자 자료형의 변환
        - 값을 유지하려고 함.
            
        - 이진수 표기는 달라질 수 있다.
            
            → float ↔ int
            
2. 개체 포인터
    
    - 변수형 체크 후 부모 클래스를 자식 클래스로 변환한다.
    - 컴파일 시에만 체크할 수 있다. → 정적
    - 실행 도중 크래시가 날 수 있음.
    
    ```c++
    Animal* myPet = new Cat(2, "Coco");
    Cat* myCat = static_cast<Cat*>(myPet);
    Dog* myCat = static_cast<Dog*>(myPet);
    myDog->GetDogHouseName();
    ```
    
    - `Dog* myCat = static_cast<Dog*>(myPet);`
        - 컴파일은 된다. Dog클래스의 멤버를 가지고 있지 않아서 크래시가 날 수 있다.
            
            → 컴파일러가 확인하는 것은 개와 동물
