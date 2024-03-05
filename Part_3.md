# 무작정 시작하기
part2는 VS Code설치 및 유용한 단축키를 알려주는 강의라 생략합니다.

## HTML 코드의 구조
!DOCTYPE html: 문서의 HTML 버전을 지정한다. 현재 웹 표준 및 가장 많이 사용하는 버전이 HTML5

HTML1 > HTML2 > HTML3 > HTML4 > XHTML > HTML5(표준)

옛날 사이트를 유지보수 및 호환하기 위해 있는 버전이 XHTML

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/915cd36f-6b70-4faf-8e64-65045355bc8a)
XHTML 사이트는 코드를 확인해보면 DOCTYPE html로 끝나지 않고 위 사진처럼 추가 문서가 작성되어 있음

<> : 시작태그

</> : 종료태그

```<html> ~ </html>``` : 문서 **전체**의 범위. HTML 문서가 어디에서 시작하고, 어디에서 끝나는지 알려주는 역할

```<head> ~ </head>``` : 문서의 **정보**를 나타내는 범위. 웹 브라우저가 해석해야 하는 웹 페이지의 제목, 설명, 미디어 위치, CSS 같은 웹페이지에 보이지 않는 정보를 작성하는 범위

```<body> ~ </body>``` : 문서의 **구조**를 나타내는 범위. 사용자 화면을 통해 보여지는 로고, 헤더, 푸터, 네비게이션, 메뉴, 버튼...등 웹페이지의 보여지는 구조를 작성하는 범위

HTML의 head부분에 css파일과 js파일을 연결시킬 수 있다.

CSS의 경우 head부분에 link태그를 통해 연결할 수 있음

JS는 head 부분에 script태그를 통해 연결할 수 있음

CSS를 별도의 파일이 아닌 html파일 내부에 작성하고 싶은 경우 head태그 안에 style태그 안에 작성할 수 있다

```<title> ~ </title>``` : HTML 문서의 **제목**을 정의한다. 브라우저 탭의 이름에 해당함

```<link rel="stylesheet" herf="main.css">``` : rel은 가져올 문서와의 **관계**를 나타낸다. href는 가져올 문서의 **경로(파일 위치)** 를 나타낸다

```<style> ~ </style>``` : HTML문서 안에 직접 CSS를 작성하는 경우 사용

```<script src="main.js"></script>``` : src를 통해 JS파일 가져올 때 사용 가능, consol.log()처럼 JS 문법을 HTML 문서 안에 작성하는 경우에도 사용

```<meta name="author" content="HI!" />``` : 메타태그는 HTML 문서의 제작자, 내용, 키워드 같은 여러 정보를 검색엔진이나 브라우저에게 제공하기 위해 사용
