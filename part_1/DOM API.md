# DOM API
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/036cbda2-243b-41b3-9d03-5e05701c3e57)

DOM이란 Document Object Mode의 약어로, HTML의 구조를 의미함.

JS에서 HTML을 제어하는 명령들 = DOM API

HTML에서 JS파일을 연결했지만, HTML은 위에서 아래로 순차적으로 읽어 실행하는 프로그램이기에 JS파일이 연결되는 코드의 위치에 따라 body의 코드가 실행이 안될 수 있음. 

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/a89f9014-a98e-4345-b88e-bb516c7e61c7)

(defer 속성을 통해 html 문서를 모두 읽고 js 파일을 실행 가능)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/05c670cd-d6e3-41bc-81a9-34b835e6e788)

1. const 함수를 통해 boxEL이라는 변수를 생성, document라는 브라우저에서 이미 정의된 객체가 담기는데 해당 객체를 선택하기 위해 querySelecter라는 메소드를 통해 .box로 css선택자를 사용하여 box 객체를 boxEL 변수에 담는다.

(querySelector 명령어는 찾는 요소들 중 가장 처음 찾은 요소 하나만 반환한다)

2. addEventListener()는 두개의 인수를 넣을 수 있는데, 첫번째는 어떤 발생 이벤트에 대한 정보를 넣을 수 있음. (ex. click이라는 이벤트는 해당 객체를 클릭한 경우 이벤트가 발생하는 것) 두번째 인수에는 function() 처럼 익명의 함수를 정의할 수 있다. 해당 부분에는 작성한 함수의 작업이 발생하는 것 = 실행할 코드.(handler라고 부른다)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/8d3c6f78-fc0f-4131-a241-de53208d25dd)

1. classList: 해당 요소의 클래스에 대한 정보 객체를 의미함.

isContains 변수에 새로운 객체의 속성인 active를 추가한 것. contains 명령을 통해 active라는 객체가 있는지 bool형으로 확인.

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/8d29bad3-ea9e-4091-b77c-b1a4dbc50418)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/161cbdcb-d113-4136-a098-db5a38aa3a80)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/3e32ae2f-ee15-41f8-b05d-9a8429270889)

querySelectorAll을 사용하면 해당 요소를 모두 선택함.

forEach 메소드로 저장된 모든 요소에 반복해서 특정 함수를 실행. (일반적인 프로그래밍의 for 반복문과 유사한 형태)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/eeb6f2b7-45e4-4ca2-8772-946ac7157741)

 1. 값을 얻는(추출)하는 용도의 API는 Getter
 2. 값을 지정(저장)하는 용도의 API는 Setter 
