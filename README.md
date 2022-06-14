# facade_pattern
퍼사드 패턴

**1.개요**
 
 - 퍼사드 패턴은 구조패턴의 한종류이다.
 - 서브시스템들의 공통적인 기능을 정의하는 단순화된 상위 수준의 인터페이스를 정의하는 패턴이다.
 - 서브시스템들 사이의 종속성을 줄일 수 있다.


**2.사용이유**

 - 복잡한 Subsystem에 대해 간단한 인터페이스를 제공하고자 할떄 유용하다.
 - Client와 구현 클래스 사이에 또는 Subsystem과 다른 Subsystem들 사이에 의존관계가 많을 경우에 이를 감소 시킬때 유용하다.


**3.장단점**

  **#장점**
  
   - Subsystem 간의 결합도를 낮출 수 있다.
   - Client 입장에서 Subsystem을 사용해야 할때 다루어야 할 객체의 수를 줄여준다.
   - Client 입장에서 좀 더 간결하게 코드를 알아볼 수 있게 해준다.
  
  **#단점**
  
   - 다른 구성요소에 대한 메소드 호출을 처리하기 위해 래퍼 클래스를 많이 만들어야 한다.
   - 시스템이 더 복잡해지고 개발시간도 늘어나면서 성능의 저하도 있을 수 있다.

**4.사용라이브러리**

 - 스프링 : Spring MVC 스프링이 제공하는 대부분의 기술 독립적인 인터페이스와 그 구현체
