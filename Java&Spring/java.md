## [JAVA]()

---

### 1. 추상 클래스 vs 인터페이스

#### 추상클래스

- 서로 관련성이 높은 클래스 간에 사용
- 상속을 받아서 기능을 이용하고 확장
- static 이나 final 이 아닌 필드를 지정할 수 있고, public, protected, private 메소드를 가질 수 있다.

#### 인터페이스

- 주로 서로 관련성이 없는 클래스들간에 사용
- 함수의 구현을 강제하기 위해서 사용

- 변수는 public static final만 가질 수 있다.
- 메소드는 public abstract만 가질 수 있다.
  But 자바8 defalut method, 자바9 private method 사용가능.

#### SAM(Single Abstract Method)

- Functional Interface 의 필수 조건(lambda식 사용 가능)
