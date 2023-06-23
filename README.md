# Comento BackEnd 


## HomeWork1 
개발환경세팅 & 테스트

1. 개발환경 세팅

   * JDK-11 사용, Spring FrameWork 5.1.8 사용

   * Eclipse 2021-09 (4.21.0) 사용 - 과제설명 pdf 버전 이클립스에서 STS 다운로드 오류가 계속 발생해서 상위버전으로 사용

   * MySql 8.0.21 사용 - MySql DB를 이미 사용중이여서 MariaDB대신 MySql DB사용

2. 테스트

   * Mybatis 사용해서 movie 테이블 data 출력하기 (완료)

3. 느낀점

   * 처음으로 이클립스를 사용해봤는데 불편한 점이 너무 많았다..

   * 이클립스를 설치하고 환경설정하는 과정에서 많은 오류가 발생해서 많은 시간이 걸렸다.
  
     

## HomeWork2 
1. REST API, HTTP 통신 학습

2. URL 입력 -> 서버 응답 과정 학습

3. API 개발하고 활용문서 작성하기

### 1. REST API 와 HTTP 통신이란?

  HTTP 통신이란?

  * 브라우저와 서버가 통신할 수 있도록 만들어주는 여러 프로토콜 가운데 한 종류

  * 웹 브라우저와 웹 서버 사이에 HTML문서를 주고받는데 쓰이는 통신 프로토콜

  * 비연결성 프로토콜이며 요청과 응답방식으로 작동
  
  REST API란

  * 말그대로 REST기반으로 서비스 API를 구현한 것
    
  * REST - HTTP URI를 통해 자원을 명시하고, HTTP Method(POST, GET, PUT, DELETE)를 통해 해당 자원에 대한 CRUD Operation을 적용하      는 것을 의미한다.
    
  REST API 설계

  * URI는 정보의 자원을 표현해야 함

  * 자원에 대한 행위는 HTTP Method(POST, GET, PUT, DELETE 등)로 표현

  

### 2. URL 입력 -> 서버 응답 과정 

  1. 웹 브라우저에 URL 입력

  2. 웹 브라우저가 도메인명의 IP주소 조회

  3. 웹 브라우저가 서버와의 TCP 연결 시작

  4. 웹 브라우저가 HTTP 요청을 서버로 전송

  5. 웹 서버가 요청을 처리하고 응답을 전송

  6. 웹 브라우저가 콘텐츠 렌더링

    
### 3. API 활용문서
  1. 개발한 API 

     다른 프로젝트에 있습니다. 빠른 시일내로 새로 올리겠습니다.
     * 회원의 아이디를 받아서 회원의 정보를 보내주는 API
  
     
     * 학과를 받아서 그 학과의 게시글을 보내주는 API

   
  2. API 활용문서

     * 회원정보API - 클라이언트가 RequestParam 방식으로 응답을 요청하고 Json 포맷으로 데이터를 응답
  
     * 게시글API - 클라이언트가 Json 포맷을 정해진 url에 post하면 Json 포맷으로 데이터를 응답

   
