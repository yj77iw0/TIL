### ``JSON`` 을 배우기 전 개념 정리

* HTTP -> ``Hypertext Transfer Protocal`` 의 약자
* Hypertext -> 사이트에서 이용되고 있는 ``link`` 들만 말하는 것이 아니라, 전반적으로 쓰여자고 있는 ``문서`` 나 ``이미지 파일`` 들을 포함해서 말한다.
  * 브라우저 위에서 동작하고 있는 ``웹 사이트`` 나 ``웹 어플리케이션`` 같은 ``Client`` 들이 ``Server`` 와 통신할 수 있는지를 정의한 것이다.
  * 어떻게 이 ``Hypertext`` 를 서로 주고 받을 수 있는지 규약한 ``Protocal`` 의 하나이다.
  * ``Client`` 가 ``Server`` 에게 데이터를 요청할 수 있고, ``Server`` 는 ``Client`` 가 요청한 것에 따라서 응답을 ``Client`` 에게 보내주는 방식을 의미한다.
* AJAX -> ``Asynchronous JavaScript And XML`` 의 약자
  * ``웹 페이지`` 에서 동적으로 ``Server`` 에게 데이터를 주고 받을 수 있는 기술을 의미한다.
* XHR -> ``XMLHttpRequest``
  * 간단하게 ``Server`` 에게 데이터를 요청하고 받아올 수 있다.
* XML -> ``HTML`` 과 같은 ``MARKUP`` 언어 중에 하나다.
  * ``HTML`` 과 같이 데이터를 표현할 수 있는 방법이다.
  
### ``JSON`` 에 대하여

* XML은 불필요한 태그들이 많이 들어가서 ``사이즈`` 도 커질 뿐만 아니라 ``가독성`` 도 좋지 않기에 많이 사용되고 있지 않다.
  * 때문에 요즘에는 ``XML`` 대신 ``JSON`` 을 많이 사용하고 있다.
* JSON -> ``JavaScript Object Notation`` 의 약자
  * 데이터를 주고 받을 때 쓸 수 있는 가장 간단한 ``파일 형식`` 이다.
  * ``JavaScript 객체 리터럴`` , ``배열`` , ``스칼라 데이터`` 를 표현하는 ``텍스트 기반``의 방식
  * 1999년도 ``ECMAScript`` 3번째 버전에 쓰여지는 ``오브젝트`` 에 큰 영감을 받아 만들어진 ``데이터 포맷`` 이다.
  * ``Key`` 와 ``Value`` 로 이루어져 있다.
  * ``컴퓨터 프로그램`` 의 ``변수`` 값을 표현하는 데 적합하다.
  * ``브라우저`` 뿐만 아니라 ``모바일`` 에서 ``Server`` 와 데이터를 주고 받을 때,
  * 또는 ``Server`` 와 통신을 하지 않아도 ``Object`` 를 파일 시스템에 저장할 때도 ``JSON`` 데이터 타입을 많이 이용하고 있다.
* JSON의 장점 ->
  * ``가독성`` 이 좋다.
  * ``Text`` 를 기반으로 해 가볍다.
  * ``프로그래밍 언어`` 나 ``플랫폼`` 에 상관없이 쓸 수 있다.
    * C, Python, JAVA 등 언어에 상관없이 ``JSON`` 으로 ``직렬화된 오브젝트`` 를 언어의 특징에 맞게 오브젝트로 변환하고, 다시 ``JSON`` 으로 직렬화 하는 것을 지원해준다.
    * 또는 많이 쓰여지고 있는 ``외부 라이브러리`` 를 통해서 이런 것들이 가능하게 된다.
* JSON의 단점 ->
  * ``주석`` 을 지원하지 않는다.
  * ``날짜``, ``시간`` 데이터를 지원하지 않는다.
