# coreJavaScript
---
<p align="center">
    <img src="/image/main.png">
</p>

---
> 자바스크립트의 핵심 개념과 동작 원리를 책을 통해 이해한 후 해당 내용을 정리하기 위해 만든 기록지입니다.

## 1. Index
##### 01. 데이터 타입 
##### 02. 실행 컨텍스트
##### 03. this
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
__01장.  데이터 타입__ 😜

| 큰 제목 | 작은 제목 | 페이지 | 작성자 | 완료여부
| :-------- | :----------------- | :--------: | :--------: | :--------: |
| 데이터 타입의 종류 |  | 1 | Local | :heavy_check_mark: |
| 데이터 타입의 관한 배경지식 | 메모리와 데이터 | 3 | Local | :heavy_check_mark: |
|  | 식별자와 변수 | 3 | Local | :heavy_check_mark: |
| 변수 선언과 데이터 할당  | 변수 선언 | 5 | Local | :heavy_check_mark: |
|  | 데이터 할당 | 6 | Local | |
| 기본형 데이터와 참조형 데이터 | 불변값 | 8 | Santos | |
|  | 가변값 | 10 | Santos | |
|  | 변수 복사 비교 | 15 | Santos | |
| 불변 객체 | 불변 객체를 만드는 간단한 방법 | 20 | Santos | |
|  | 얕은 복사와 깊은 복사 | 25 | Santos | |
| undefined와 null | | 29 | Santos | |
| 정리 | | 34 | Santos | |


__02장.  실행 컨텍스트__ 😝

| 큰 제목 | 작은 제목 | 페이지 | 작성자 | 완료여부
| :-------- | :----------------- | :--------: | :--------: | :--------: |
| 실행 컨텍스트란? | - | 36 | Local | :heavy_check_mark: |
| VariableEnviroment | environmentRecord와 호이스팅 | 42 | Local | :heavy_check_mark: |
|  | 스코프, 스코프 체인, outerEnvironmentRefernce | 53 | Local | :heavy_check_mark: |
| 변수 선언과 데이터 할당  | 변수 선언 | 5 | Santos | :heavy_check_mark: |
| this |  | 63 | Santos | |
| 정리 | | 63 | Santos | |


__03장.  this__ 😋

| 큰 제목 | 작은 제목 | 페이지 | 작성자 | 완료여부
| :-------- | :----------------- | :--------: | :--------: | :--------: |
| 상황에 따라 달라지는 this | 전역 공간에서의 this | 65 | Santos | :heavy_check_mark: |
|  | 메서드로서 호출할 때 그 메서드 내부에서의 this | 66 | Santos | :heavy_check_mark: |
|  | 함수로서 호출할 때 그 함수 내부에서의 this | 72 | Santos | :heavy_check_mark: |
|  | 콜백 함수 호출 시 그 함수 내부에서의 this | 76 | Santos | :heavy_check_mark: |
|  | 생성자 함수 내부에서의 this | 78 | Santos | |
| 명시적으로 this를 바인딩하는 방법 | call 메서드 | 78 | Local | |
|  | apply 메서드 | 81 | Local | |
|  | call/apply 메서드의 활용 | 82 | Local | |
|  | bind 메서드 | 87 | Local | |
|  | 화살표 함수의 예외사항 | 90 | Local | |
|  | 별도의 인자로 this를 받는 경우(콜백 함수 내에서의 this) | 91 | Local | |
| 정리 |  | 93 | Local | |
