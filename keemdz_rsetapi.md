# REST API

## REST

- REST의 정의
    1. "Representational State Transfer"의 약자. 
    2. 자원의 표현(이름)으로 구분하여 해당 자원의 상태를  주고 받는 모든 것
    3. 월드 와이드 웹(www)과 같은 분산 하이퍼 미디어 시스템을 위한 소프트웨어 개발 아키텍처의 한 형식
- REST의 개념

    HTTP URI(Uniform Resource Identifier)를 통해 자원(Resource)을 명시하고, HTTP Method(POST, GET, PUT, DELETE)를 통해 해당 자원에 대한 CRUD(Create, Read, Update, Delete) Operation을 적용하는 것을 의미한다.

## REST의 장단점

### 장점

- 서버와 클라이언트의 역할을 명확하게 분리한다.
- 여러가지 서비스  디자인에서 생길 수 있는  문제를 최소화한다.
- HTTP 표준 프로토콜에 따르는 모든 플랫폼에서 사용이 가능하다.

### 단점

- 표준이 존재하지 않는다.
- 구형 브라우저가 아직 제대로 지원하지 못하는 부분이 존재한다.
- 사용할 수 있는 메소드가 4가지 밖에 없다

## API

1. "Application Programming Interface"의 약자. 
2. 응용 프로그램에서 사용할 수 있도록, 운영 체제나 프로그래밍 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스

# REST API

REST 기반으로 API를 구성한 것

## REST API의 특징

- REST 기반으로 시스템들을 분산해  확장성과 재사용성을 높여 유지보수 및 운용을 편리하게 할 수 있다.
- REST는 HTTP 표준을 기반으로 구현하므로, HTTP를 지원하는 프로그램 언어로 클라이언트, 서버를 구현할 수 있다.
- REST API를 제작하면 델파이 클라이언트 뿐 아니라, 자바, C#, 웹 등을 이용해 클라이언트를 제작할 수 있다.

## REST API 설계 규칙

- URI는 정보의 자원을 표현해야 한다. (리소스명은 동사보다는 명사를 사용)
- 자원에 대한 행위는 HTTP Method(GET, POST, PUT, DELETE 등)로 표현
- 슬래시 구분자(/)는 계층 관계를 나타내는 데 사용하며 URI 마지막 문자로 사용하지 않는다.
- 하이픈(-)은 URI 가독성을 높이는데 사용하지만 밑줄(_)은 URI에 사용하지 않는다.
- URI 경로에는 소문자가 적합하다.

## 참고 사이트

- [https://gmlwjd9405.github.io/2018/09/21/rest-and-restful.html](https://gmlwjd9405.github.io/2018/09/21/rest-and-restful.html)
- [https://meetup.toast.com/posts/92](https://meetup.toast.com/posts/92)
- [https://ko.wikipedia.org/wiki/REST](https://ko.wikipedia.org/wiki/REST)