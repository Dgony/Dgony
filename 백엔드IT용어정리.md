**본 정리 내용은 멀티캠퍼스에서 학습한 내용을 담았다.**
<details>
<summary>키워드로 찾아가기</summary>

[HTML](#html)  
[CSS](#css)  
[JS](#js)  
[HTTP](#http)  
[HTTPS](#https)  
[URL](#url)  
[URI](#uri)    
[WAS](#was)  
[SERVLET](#servlet)  
[JSP](#JSP)  
[SNIPPET](#snippet)  
[JQUERY](#jqeury)  

[](#)

</details>

<hr>

# 용어 정리

## HTML
* **Hyper Text Markup Language**   
<u>Text(문자)와 Markup(<>) 문법을 통해 웹 페이지의 내용을 구조화하는 언어</u>    
<br>
Hyper - 초월하는(다른 페이지 이동) / Text - 문자로 / Markup - <>안에 넣는 문법 / Language - 언어  
웹 페이지에 보이는 뼈대의 역할을 담당한다.  
웹 브라우저는 HTML, CSS, JS만 읽을 수 있기 때문에 반드시 이 언어들로만 웹 페이지를 만들어야 한다.  
<>태그와 문자로 다른 페이지와 연결할 수 있다.  
<>속 태그는 대소문자 구분을 하지 않는다. 하지만 <>태그에 속성을 작성한다면 소문자로 작성해야 인식할 수 있다.  


## CSS
* **Cascading Style Sheet**  
<u>계단식으로 적용되는 스타일 시트로, 웹 페이지 표시 모양을 결정한다.</u>  
<br>
HTML, 마크업 언어가 우베페이지에 어떤 특성으로, 어떤 모양으로 표시될 지 결정한다.  
JS와 함께 Internal / External / Inline 방식 중 하나의 방법으로 적용할 수 있다.  
CSS3부터는 애니메이션도 적용할 수 있게 되었다.  

### CSS 선택자  
1. 기본 선택자  
전체, 유형, 클래스, ID, 특성 선택자  포함
2. 가상 선택자  
3. 속성 선택자   

## JS
* **JavaScript**  
<u>HTML의 구조를 CSS의 특성대로 구성한 페이지의 데이터 전달이나 각종 기능을 맡는다.</u>    
<br>
JAVA와 흡사한 부분이 많고 JAVA에 비해 더 나중에 만들어진 언어이다. 그래서 욕을 좀 먹었다고 들었다.  
JAVA에 비해 허술한 부분이 있지만, JQuery와 es6등의 문법으로 많이 발전했다.  
또한 크롬 브라우저에서 가장 빠른 속도를 가진 언어이자, 가장 오래 쓰인 언어이기 때문에 점유율도 높다. 웹 개발에서 빼놓고 말할 수 없는 언어인 것이다.  
JS는 프론트엔드와 백엔드를 이어주는 언어이기 때문에 백엔드 개발자로서 잘 알아두어 하는 언어라고 생각한다.  
JS를 위한 framework는 reac, vue, angular, bootstrap 드이 있다.


## HTTP
* **Hyper Text Transfer Protocol**  
<u>웹 서버와 브라우저가 정보를 주고받기 위한 프로토콜(규약), HTML과 같은 Text로 이루어지기에 붙은 이름</u>  
<br>
https://dgony.github.io//daily-record-1/  <== 이 URI를 예로들어 설명하면,    
https: ==> 웹 브라우저의 정보 전송 규약  
dgony.github.io ==> 네트워크 연결 주소 + port  
daily-record-1 ==> 요청하는 문서(페이지, 데이터)의 위치와 이름  
<br>
80번 포트 사용  
클라이언트와 웹서버 간의 전송은 HTTP 규약을 따르도록 정해져 있다.  
HTTPS에 비해 보안성이 떨어지고 데이터가 해킹될 수 있음  
1. 무연결성(Connectionless) : 통신시 연결을 유지 않는다. 한 번 연결하고, 주고받고, 바로 끊는다.  
2. 무상태성(Stataless) : 요청할 때마다 다른 작업을 실시한다. 이전에 연결했던 클라이언트임을 ID를 사용해 저장해두었다가 인식하는 방식이다.  
요청정보(Request)를 저장해두었다가 조건에 맞는 응답정보(Response)를 반환한다. 

### HTTP 주요 응답 코드  
1. 200 ==> ok  
2. 400 ==> bad request  
3. 404 ==> not found  
4. 500 ==> interanl error  

## HTTPS
* **Hyper Text Transfer Protocol Secure**  
<u>HTTP와 동일하지만 보안이 강화된 형태.</u>   
<br>
443번 포트 사용  
SSL(Secure Sockets Layer) 또는 TLS(Transport Layer Security) 인증서를 통해 데이터를 암호화하여 전송, 은행같은 민감한 사이트는 대부분 이 방식을 채택.  
HTTP에 비해 상대적으로 느리지만 하드웨어의 현대화에 따라 큰 차이는 없어짐




## WAS
* **Web Application Service**  


## SERVLET



## JSP


## SNIPPET
* **코드조각모음**   
<u>개발 언어에서 특정 접두어를 입력하면 지정한 템플릿이 작성되게 하는 기능</u> 
<br>  
코드를 작성하기 위한 반복 작업을 줄여준다.  
Snippet의 예로 이 md 파일을 작성 중인 VSCODE에서 html파일을 만든 후, html:5 라는 접두어를 입력하게 되면 html파일 작성을 위한 기본 템플릿이 자동 작성되게 된다.  

## URL
* **Uniform Resource Locator**   
<u>인터넷 상에 존재하는 자원의 위치를 나타내는 주소.</u> 
<br>  
처음 웹에대해 배울 때 로컬 파일로 웹 페이지를 만들었기 때문에 살짝 헷갈렸던 개념.  

## URI  
* **Uniform Resource Identifier**  
------------추후서술--------------

## UI
* **User Interface**  
<u>쉽게 말해서 사용자에게 보여지는 화면</u>
<br>

## UX
* **User Experience**  
<u>사용자 경험. 사용자가 사이트를 이용하는 흐름</u>
<br>


## JQEURY 
* <u>JS를 더 짧은 길이로 이용할 수 있도록 간략화한 방법</u>   
<br>
JS를 더 잘 이용하기 위한 방법으로, 모두가 이해할 수 있는 준말 정도로 말할 수 있다.  

## DOM Tree
* ****  
<u></u>
<br>



## OOP
* **Object-Oriented Programming**   
<u>객체지향적 언어를 이르는 말로, 프로그래밍은 명령어의 목록으로 보는 것이 아니라 여러 독립된 객체들의 상호작용으로 프로그램을 구성하는 것을 의미한다.  
부품 조립식 언어라는 표현이 이해하기 쉬웠다.</u>  
<br>

## 
* ****
<u></u>
<br>

##  
* **** 
<u></u>
<br>

## 
* **** 
<u></u>
<br>

## 
* **** 
<u></u>
<br>