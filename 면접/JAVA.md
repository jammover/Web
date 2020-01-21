1. String, StringBuilder, StringBuffer의 차이를 설명하세요.

일단, 공통점은 String(문자열)을 저장하고 관리하는 클래스라는 것!
차이점은 String은 immutable(불변)하고, StringBuilder, StringBuffer는 mutable(가변)하다는 것이다.

String은 new 연산을 통해 생성되면 그 인스턴스의 메모리 공간은 절대 불변!
그래서 +연산이나 concat을 이용해서 문자열에 변화를 줘도, 새로운 String 객체를 만들어진다.(=새로운 메모리 공간이 만들어진다.)

String의 단점 : 가비지 콜렉터에 의해 제거되어야 한다 & 계속해서 객체가 만들어지

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU5MjMyNzg4OSw3MzYxNzU0MDldfQ==
-->