1. String, StringBuilder, StringBuffer의 차이를 설명하세요.

일단, 공통점은 String(문자열)을 저장하고 관리하는 클래스라는 것!
차이점은 String은 immutable(불변)하고, StringBuilder, StringBuffer는 mutable(가변)하다는 것이다.

String은 new 연산을 통해 생성되면 그 인스턴스의 메모리 공간은 절대 불변!
그래서 +연산이나 concat을 이용해서 문자열에 변화를 줘도, 새로운 String 객체를 만들어진다.(=새로운 메모리 공간이 만들어진다.)

String의 단점 : 가비지 콜렉터에 의해 제거되어야 한다. & 문자열 연산이 많아질 때 계속 객체를 만드는 오버헤드가 발생한다.
String의 장점 : 조회연산을 빠르게 할 수 있다. & 불변하기 때문에 멀티쓰레드 환경에서 동기화를 신경쓸 필요가 없다.

StringBuilder VS. StringBuffer 
StringBuffer는 멀티쓰레드환경에서 synchronized 키워드가 가능하므로 동기화가 가능하다. 즉, thread-safe하다.
StringBuilder는 동기화를 보장하지 않는다.

2. 객체지향언어의 특징 3가지만 설명해보세요.

추상화, 캡슐화, 상속, 다형성

4. 객체지향에 대해서 설명해보세요.

5. NIO(New Input-Out)에 대해 설명하세요.

6. 자바의 기본 자료형과 참조 자료형에 대해 설명해 보세요.

7. 오버로딩과 오버라이딩의 차이점을 말해보세요.

오버로딩은 메소드는 같은 이름의 메소드를 여러개 가지면서 매개변수의 유형과 개수가 다르도록 하는 기술이고,
오버라이딩은 상위클래스가 가지고 있는 메소드를 하위 클래스에서 재정의해서 사용하는 것이다.

9.  Call by Value, Call by Reference의 차이는 무엇인가요?

함수호출 방식에는  두가지, Call by Value(값에 의한 호출), Call by Reference(참조에 의한 호출)이 있다.


11.  접근제어자에 대해 설명하세요.
 
12. 추상클래스와 인터페이스에 대해 설명하세요.
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NjgxMjA5NzMsLTE4OTc5MDQ2MTMsLT
E1NjQ0MDcyNDgsLTE1MDc2MDgzMjgsNzkxMzk0NzYzLDE3Mjkx
MTQ4NzEsNzM2MTc1NDA5XX0=
-->