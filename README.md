# coreJavaScript
---
<p align="center">
    <img src="/image/main.png">
</p>

---
> 자바스크립트의 핵심 개념과 동작 원리를 책을 통해 이해한 후 해당 내용을 정리하기 위해 만든 기록지입니다.

## 1. Index
##### 01. [데이터타입](#01장.데이터타입)
##### 02. [실행컨텍스트](#02장.실행컨텍스트)
##### 03. [this](#03장.this)
##### 04. 콜백 함수
##### 05. 클로저
##### 06. 프로토타입

## 2. Table (ToDo)
```
Rule 😎
01. 작성자를 뺴먹지 않고 작성한다. 
02. 한 페이지의 정리가 끝나면 큰 제목과 작은 제목의 내부 링크를 연결한다. 
03. 작성 내용은 default 포맷을 참고하여 작성한다. (contents/default.md 참고)
```
__01장.데이터 타입__

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 데이터 타입의 종류 |  | 1 | [Local][Local] | :heavy_check_mark: |
| 데이터 타입의 관한 배경지식 | 메모리와 데이터 | 3 | [Local][Local] | :heavy_check_mark: |
|  | 식별자와 변수 | 3 | [Local][Local] | :heavy_check_mark: |
| 변수 선언과 데이터 할당  | 변수 선언 | 5 | [Local][Local] | :heavy_check_mark: |
|  | 데이터 할당 | 6 | [Local][Local] | |
| 기본형 데이터와 참조형 데이터 | 불변값 | 8 | [Santos][Santos] | |
|  | 가변값 | 10 | [Santos][Santos] | |
|  | 변수 복사 비교 | 15 | [Santos][Santos] | |
| 불변 객체 | 불변 객체를 만드는 간단한 방법 | 20 | [Santos][Santos] | |
|  | 얕은 복사와 깊은 복사 | 25 | [Santos][Santos] | |
| undefined와 null | | 29 | [Santos][Santos] | |
| 정리 | | 34 | [Santos][Santos] | |


__02장.  실행 컨텍스트__

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 실행 컨텍스트란? | - | 36 | [Local][Local] | :heavy_check_mark: |
| VariableEnviroment | environmentRecord와 호이스팅 | 42 | [Local][Local] | :heavy_check_mark: |
|  | 스코프, 스코프 체인, outerEnvironmentRefernce | 53 | [Local][Local] | :heavy_check_mark: |
| 변수 선언과 데이터 할당  | 변수 선언 | 5 | [Santos][Santos] | :heavy_check_mark: |
| this |  | 63 | [Santos][Santos] | |
| 정리 | | 63 | [Santos][Santos] | |


__03장.  this__ 😋

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 상황에 따라 달라지는 this | 전역 공간에서의 this | 65 | [Santos][Santos] | :heavy_check_mark: |
|  | 메서드로서 호출할 때 그 메서드 내부에서의 this | 66 | [Santos][Santos] | :heavy_check_mark: |
|  | 함수로서 호출할 때 그 함수 내부에서의 this | 72 | [Santos][Santos] | :heavy_check_mark: |
|  | 콜백 함수 호출 시 그 함수 내부에서의 this | 76 | [Santos][Santos] | :heavy_check_mark: |
|  | 생성자 함수 내부에서의 this | 78 | [Santos][Santos] | |
| 명시적으로 this를 바인딩하는 방법 | call 메서드 | 78 | [Local][Local] | |
|  | apply 메서드 | 81 | [Local][Local] | |
|  | call/apply 메서드의 활용 | 82 | [Local][Local] | |
|  | bind 메서드 | 87 | [Local][Local] | |
|  | 화살표 함수의 예외사항 | 90 | [Local][Local] | |
|  | 별도의 인자로 this를 받는 경우(콜백 함수 내에서의 this) | 91 | [Local][Local] | |
| 정리 |  | 93 | [Local][Local] | |


__04장.  콜백함수__ 😘

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료여부</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 콜백 함수란? | | 94 | [Santos][Santos] | :heavy_check_mark: |
| 제어권 | 호출 시점 | 95 | [Santos][Santos] | :heavy_check_mark: |
|  | 인자 | 98 | [Santos][Santos] | :heavy_check_mark: |
|  | this | 100 | [Santos][Santos] | :heavy_check_mark: |
| 콜백 함수는 함수다 | | 102 | [Santos][Santos] | |
| 콜백 함수 내부의 this에 다른 값 바인딩하기 | | 103 | [Local][Local] | |
| 콜백 지옥과 비동기 제어 | | 106 | [Local][Local] | |
| 정리 | | 113 | [Local][Local] | |


__05장.클로저__ 🥸

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료여부</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 클로저의 의미 및 원리 이해| | 115 | [Santos][Santos] | :heavy_check_mark: |
| 클로저와 메모리 관리 | | 123 | [Santos][Santos] | :heavy_check_mark: |
| 클로저 활용 사례 | 콜백 함수 내부에서 외부 데이터를 사용하고자 할 때 | 125 | [Local][Local] | :heavy_check_mark: |
| | 접근 권한 제어(정보 은닉) | 129 | [Local][Local] | :heavy_check_mark: |
| | 부분 적용 함수 | 134 | [Local][Local] | |
| | 커링 함수 | 141 | [Local][Local] | |
| 정리 | | 145 | [Local][Local] | |


__06장.  프로토타입__ 🤩

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료여부</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 프로토타입의 개념 이해| constructor, prototype, instance | 147 | [Santos][Santos] | :heavy_check_mark: |
| | constructor 프로퍼티 | 157 | [Santos][Santos] | :heavy_check_mark: |
| 프로토타입 체인 | 메서드 오버라이드 | 160 | [Local][Local] | :heavy_check_mark: |
| | 프로토타입 체인 | 162 | [Local][Local] | :heavy_check_mark: |
| | 객체 전용 메서드의 예외사항 | 168 | [Local][Local] | |
| | 다중 프로토타입 체인 | 171 | [Local][Local] | |
| 정리 | | 173 | [Local][Local] | |


__07장.  클래스__ 🤩

| <center>큰 제목</center> | <center>작은 제목</center>| <center>페이지</center> | <center>작성자</center> | <center>완료여부</center>
| -------- | ----------------- | :--------: | :--------: | :--------: |
| 클래스와 인스턴스의 개념 이해 | | 175 | [Santos][Santos] | :heavy_check_mark: |
| 자바스크립트의 클래스 | | 178 | [Santos][Santos] | :heavy_check_mark: |
| 클래스 상속 | 기본 구현 | 181 | [Local][Local] | :heavy_check_mark: |
| | 클래스가 구체적인 데이터를 지니지 않게 하는 방법 | 189 | [Local][Local] | :heavy_check_mark: |
| | constructor 복구하기 | 193 | [Local][Local] | |
| | 상위 클래스에의 접근 수단 제공 | 195 | [Local][Local] | |
| ES6의 클래스 및 클래스 상속 | | 197 | [Santos][Santos] | :heavy_check_mark: |
| 정리 | | 200 | [Santos][Santos] | :heavy_check_mark: |

## 3. Reference

- [코어자바스크립트][core-javaScript]

[core-javaScript]: https://www.aladin.co.kr/shop/wproduct.aspx?ISBN=K532636268&start=pnaver_02
[Santos]: https://github.com/SangchoKim
[Local]: https://github.com/blocallee
