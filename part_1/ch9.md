ch7,8 은 CSS관련 내용이며 별도 정리는 생략합니다.

# JS 선행 학습
html에서 javascrip 파일을 연결하는 방법: html의 head안에 script 태그를 사용해서 src로 경로 지정해준다.

참고로 JS 파일을 작성할 때, 코드를 작성하고 ; 을 붙이는게 정규식이지만 세미콜론을 붙이지 않아도 일반적인 상황에서 작동하는데 문제는 없다.

## 표기법 (프로그래밍의 표기법)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/ea5d13af-8afc-4ed2-b554-7ac91bb2c1f9)

위 이미지처럼 대시 기호를 사용해서 연결되어 단어를 표현하는 표기 방법.

컴퓨터는 대시기호를 포함해서 위 글을 하나의 단어로 인식하지만, 사람은 대시 기호로 구분해서 읽기 쉬운 문장으로 해석할 수 있다.

(대시 케이스는 html과 CSS에서 주로 사용한다.)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/840d4e0c-1642-4bb7-855c-59a41cd025f5)

흔히 언더바(_)로 연결되는 단어의 표기법. 

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/46a1243a-8f5a-40bf-90aa-aec0c0030768)

첫 글자가 소문자로 시작하고, 그 뒤로부터 이어지는 단어들 중 단어의 첫 글자는 대문자로 표기되어 이어져있어도 대문자로 각 단어를 구분할 수 있다.

(JS는 대부분의 경우 카멜 케이스로 사용한다)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/2a517014-e9fc-4245-86c6-dec10adb2e72)

카멜 케이스와 매우 유사하지만, 첫 글자도 대문자로 시작한다. 

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/5869525f-e4a3-4c90-8d45-78e47ac730e5)

많은 프로그래밍의 언어들은 기본적으로 0부터 시작함. (각 언어 및 케이스별로 다를 수 있음, JS는 0부터 시작)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/a70e69f0-8d5b-4375-8514-85c018869f8c)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/0ec24681-dea0-4d91-a792-fdc950218dbb)

한줄 주석과 여러줄 주석으로 나뉨. 쉽게 하는 방법은 ctrl+/ 

## 데이터 종류 (자료형)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/72026595-59aa-4f7c-88f7-6407cf52d62d)

### String (문자 데이터)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/21d5bd80-d99c-44ea-a87a-d9c101abbef4)

따옴표를 사용해서 문자형을 지정할 수 있음.

  ` (백틱 기호)를 사용할 경우 보관법 이라는 기능을 통해 문자열 안에 추가적인 데이터를 포함할 수 있음.

### Number (숫자 데이터 = 정수 및 부동소수점 숫자)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/74fc2f63-4d9b-4188-bb19-df3b9e98cbc5)

### Boolean (논리 데이터)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/f2c54bed-e7e8-499a-9603-f7ae3584e83f)

참과 거짓을 구분하기 위해 사용된다.

### Undefined (값이 할당되지 않은 상태)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/a3cb5c9d-7077-4c18-86d2-d30712a0f47d)

### Null (값이 비어있는 상태)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/06f28658-45e7-4075-8e3d-289f9d8e27a8)

Undeined와 Null의 차이는 Null은 값이 없는 상태를 의도적으로 넣은 것, Undefined는 애초에 해당 부분에 공간이 없던 것.

### Object (객체 데이터)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/50b40669-6dfd-4e30-960a-eb3426a917f8)

Key:Value 형태로 저장하는 데이터의 집합체

대괄호 {} 안에 지정된 데이터를 객체 변수 안에 담는다.

변수명.Key값 을 통해 해당 객체의 key에 해당하는 Value를 추출할 수 있다.

### Array (배열 데이터)
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/3f9181f0-c9a1-4517-a7b1-c163de74d9fe)

## 변수
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/579298af-099e-4427-9c07-d05b02c77a15)

var는 최근에 잘 사용하지 않는 것이 권장사항.

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/ec579e59-422a-47ac-b066-de691e5439de)

변수를 선언하고 언제든 해당 변수명을 통해 데이터를 재사용할 수 있다.

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/0c75ee62-83bb-4607-b2f7-6852bd367f20)

한번 선언한 변수를 새로운 값으로 재할당 수 있다.

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/18f2d5dd-4d97-46b5-86a6-3445c4684a10)

const를 사용할 경우 변수에 재할당할 수 없다. 

대부분의 상황에서 const를 사용하고, 변수에 재할당이 필요한 상황이 생기면 const를 let으로 변경하는 작업을 진행한다.

## 예약어
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/832acab0-f98f-4204-a3fa-83e3c10f149f)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/ba6fca33-38fd-4dba-8a60-31ea7ad568e3)

이미 기본적으로 사용되는 단어들은 변수로 지정할 수 없음. 

## 함수
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/cac2ed6b-01ba-4603-acc0-66d7a53a8cb4)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/65122d29-be6a-4775-86bc-17cb1acf9379)

function 을 통해 함수를 선언할 수 있음. **명령들을 감싸는 하나의 집합**

함수 안에는 해당 함수를 실행할 때 작업하고 싶은 명령을 코드로 작성한다 ( 대괄호 안에 )

직접 해보기:
```
function test_Drive() {
    console.log('js is so fun');
    let a = 10;
    let b = 12;
    return a+b;
};
let result = test_Drive();

console.log(result);
```
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/29addec6-3e3d-4880-8977-423a255a6ea2)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/9537772c-f0d5-451d-9ce4-655a7ddb1fa7)

함수를 선언할 때, 소괄호 안에 지정된 매개변수는 외부로부터 값을 전달받아 함수 내부에서 사용할 수 있게 해준다. (함수 내부에서만 사용 가능)

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/dbbd7c22-0fd6-4820-98d8-f45449a42c91)

함수에 이름을 지정하지 않을 수도 있다. 

이름을 직접 명시하는 것은 '함수 선언', 이름이 없는 경우 '함수 표현' 라고 말한다.

![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/3f3eff84-6bb5-4777-8e50-a2c278471cdc)

함수 안에 name, age같은 속성이 있음. getName처럼 속성에 함수가 사용될 경우 해당 데이터는 속성이 아닌 메소드 라고 부른다.

직접 해보기:
```
const getName = {
    name:'MKG',
    age:25,
    yourname:function() {
        return this.name;
    }
};

const whatisname = getName.yourname();
console.log(whatisname);

console.log(getName.yourname());
```
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/a0a6b3ff-db93-4cdc-89ab-a3ca8ce617e1)

## 조건문
![image](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/b498e632-323b-43ec-8e2c-bc5a4fe23c6a)

if문: 소괄호 안에 조건을 작성하고, 참일 경우 대괄호 안에 작성한 코드를 실행한다. 거짓일 경우 무시하고 넘어간다.

else문: if문에서 거짓으로 판단되어 넘어갈 경우 실행되는 부분. (참일 경우 else 내부 코드는 실행되지 않는다)
