# 메소드 체이닝

![스크린샷 2024-06-03 020033](https://github.com/SAMEZ-0129/FE_Study/assets/81644075/f4fdd1ed-82fe-4856-bcc5-4756c4061043)

```
const b = a.split('').reverse().join('');
```
위 코드처럼 split, reverese, join같은 메소드들이 체인처럼 연결된 형태를 ***메소드 체이닝***이라고 부른다.

메소드 체이닝은 다양한 규칙이 존재하는데, 지금 시간에서는 다루기 너무 많으니 우선 해당 개념만 이해하는 것으로 진행.

split() 메소드는 괄호 안에 들어가는 인수를 기준으로 쪼개서 배열로 변환함.

reverse는 말 그대로 배열의 순서를 뒤집음

join 메소드는 괄호 안에 들어가는 인수를 기준으로 배열을 문자로 병합하고 결과를 return한다.
