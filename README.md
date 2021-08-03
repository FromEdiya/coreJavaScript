# coreJavaScript

<p align="center">
    <img src="./image/main.png">

> 자바스크립트의 핵심 개념과 동작 원리를 책을 통해 이해한 후 해당 내용을 정리하기 위해 만든 기록지입니다.

</p>

---

<br>

## 1. Index

##### 01. 데이터타입

##### 02. 실행컨텍스트

##### 03. this

##### 04. 콜백 함수

##### 05. 클로저

##### 06. 프로토타입

##### 07. 클래스

<br>
<br>
<br>

## 2. Table (ToDo)

```
Rule 😎
00. 목차 이름을 딴 브랜치를 만들고 브랜치로 별로 push를 한다.
01. 작성자를 뺴먹지 않고 작성한다.
02. 한 페이지의 정리가 끝나면 작은 제목의 내부 링크를 연결한다.
03. 페이지 경로는 contents/인덱스.목차이름/인덱스.큰제목/인덱스-숫자.작은 제목(없다면 생략).md (한글로 입력하기)
    * ex) contents/01.데이터타입/1.데이터타입의종류/1-1.데이터타입의종류.md

04. 작성 내용은 default 포맷을 참고하여 작성한다. (contents/default.md 참고)
05. 이미지 첨부시 경로는 image/인덱스.목차이름/.(png | jpeg | jpg)
    * ex) image/01.데이터타입/byte.jpeg

06. 작성이 끝난 후 README.md 파일에서 완료 여부에 체크를 한다.
```

<br>
<br>

**01장.데이터 타입** 😜

| <center>큰 제목</center>      | <center>작은 제목</center>                                   | <center>페이지</center> | <center>작성자</center> | <center>완료</center> |
| ----------------------------- | ------------------------------------------------------------ | :---------------------: | :---------------------: | :-------------------: |
| 데이터 타입의 종류            | [데이터 타입의 종류][데이터타입의종류]                       |            1            |     [Local][local]      |  :heavy_check_mark:   |
| 데이터 타입의 관한 배경지식   | [메모리와데이터][메모리와데이터]                             |            3            |     [Local][local]      |  :heavy_check_mark:   |
|                               | [식별자와 변수][식별자와변수]                                |            3            |     [Local][local]      |  :heavy_check_mark:   |
| 변수 선언과 데이터 할당       | [변수 선언][변수선언]                                        |            5            |     [Local][local]      |  :heavy_check_mark:   |
|                               | [데이터 할당][데이터할당]                                    |            6            |     [Local][local]      |  :heavy_check_mark:   |
| 기본형 데이터와 참조형 데이터 | [불변값][불변값]                                             |            8            |    [Santos][santos]     |  :heavy_check_mark:   |
|                               | [가변값][가변값]                                             |           10            |    [Santos][santos]     |  :heavy_check_mark:   |
|                               | [변수 복사 비교][변수복사비교]                               |           15            |    [Santos][santos]     |  :heavy_check_mark:   |
| 불변 객체                     | [불변 객체를 만드는 간단한 방법][불변객체를만드는간단한방법] |           20            |    [Santos][santos]     |  :heavy_check_mark:   |
|                               | [얕은 복사와 깊은 복사][얕은복사와깊은복사]                  |           25            |    [Santos][santos]     |  :heavy_check_mark:   |
| undefined와 null              | [undefined와 null][undefined와null]                          |           29            |    [Santos][santos]     |  :heavy_check_mark:   |
| 정리                          | [정리][정리]                                                 |           34            |    [Santos][santos]     |  :heavy_check_mark:   |

<br>
<br>

**02장. 실행 컨텍스트** 😝

| <center>큰 제목</center> | <center>작은 제목</center>                    | <center>페이지</center> | <center>작성자</center> | <center>완료</center> |
| ------------------------ | --------------------------------------------- | :---------------------: | :---------------------: | :-------------------: |
| 실행 컨텍스트란?         | 실행컨텍스트란?                               |           36            |     [Local][local]      |  :heavy_check_mark:   |
| VariabledEnvironment     | VariabledEnvironment                          |           40            |     [Local][local]      |  :heavy_check_mark:   |
| LexicalEnvironment       | environmentRecord와 호이스팅                  |           42            |     [Local][local]      |                       |
|                          | 스코프, 스코프 체인, outerEnvironmentRefernce |           53            |     [Local][local]      |                       |
| this                     | [this][컨텍스트this]                          |           63            |    [Santos][santos]     |  :heavy_check_mark:   |
| 정리                     | [정리][컨텍스트정리]                          |           63            |    [Santos][santos]     |  :heavy_check_mark:   |

<br>
<br>

**03장. this** 😋

| <center>큰 제목</center>          | <center>작은 제목</center>                              | <center>페이지</center> | <center>작성자</center> | <center>완료</center> |
| --------------------------------- | ------------------------------------------------------- | :---------------------: | :---------------------: | :-------------------: |
| 상황에 따라 달라지는 this         | [전역 공간에서의 this][전역공간에서의this]                                    |           65            |    [Santos][santos]     |   :heavy_check_mark:                    |
|                                   | [메서드로서 호출할 때 그 메서드 내부에서의 this][메서드로서호출할때그메서드내부에서의this]          |           69            |    [Santos][santos]     |    :heavy_check_mark:                    |
|                                   | [함수로서 호출할 때 그 함수 내부에서의 this][함수로서호출할때그메서드내부에서의this]              |           72            |    [Santos][santos]     |          :heavy_check_mark:              |
|                                   | [콜백 함수 호출 시 그 함수 내부에서의 this][콜백함수호출시그함수내부에서의this]               |           76            |    [Santos][santos]     |                :heavy_check_mark:       |
|                                   | [생성자 함수 내부에서의 this][생성자함수내부에서의this]                             |           78            |    [Santos][santos]     |           :heavy_check_mark:             |
| 명시적으로 this를 바인딩하는 방법 | call 메서드                                             |           78            |     [Local][local]      |                       |
|                                   | apply 메서드                                            |           81            |     [Local][local]      |                       |
|                                   | call/apply 메서드의 활용                                |           82            |     [Local][local]      |                       |
|                                   | bind 메서드                                             |           87            |     [Local][local]      |                       |
|                                   | 화살표 함수의 예외사항                                  |           90            |     [Local][local]      |                       |
|                                   | 별도의 인자로 this를 받는 경우(콜백 함수 내에서의 this) |           91            |     [Local][local]      |                       |
| 정리                              | 정리                                                    |           93            |     [Local][local]      |                       |

<br>
<br>

**04장. 콜백함수** 😘

| <center>큰 제목</center>                   | <center>작은 제목</center>                 | <center>페이지</center> | <center>작성자</center> | <center>완료여부</center> |
| ------------------------------------------ | ------------------------------------------ | :---------------------: | :---------------------: | :-----------------------: |
| 콜백 함수란?                               | [콜백 함수란?][콜백함수란]                               |           94            |    [Santos][santos]     |         :heavy_check_mark:                  |
| 제어권                                     | [호출 시점][호출시점]                                  |           95            |    [Santos][santos]     |           :heavy_check_mark:                 |
|                                            | 인자                                       |           98            |    [Santos][santos]     |                           |
|                                            | this                                       |           100           |    [Santos][santos]     |                           |
| 콜백 함수는 함수다                         | 콜백 함수는 함수다                         |           102           |    [Santos][santos]     |                           |
| 콜백 함수 내부의 this에 다른 값 바인딩하기 | 콜백 함수 내부의 this에 다른 값 바인딩하기 |           103           |     [Local][local]      |                           |
| 콜백 지옥과 비동기 제어                    | 콜백 지옥과 비동기 제어                    |           106           |     [Local][local]      |                           |
| 정리                                       | 정리                                       |           113           |     [Local][local]      |                           |

<br>
<br>

**05장.클로저** 🥸

| <center>큰 제목</center>   | <center>작은 제목</center>                        | <center>페이지</center> | <center>작성자</center> | <center>완료여부</center> |
| -------------------------- | ------------------------------------------------- | :---------------------: | :---------------------: | :-----------------------: |
| 클로저의 의미 및 원리 이해 | 클로저의 의미 및 원리 이해                        |           115           |    [Santos][santos]     |                           |
| 클로저와 메모리 관리       | 클로저와 메모리 관리                              |           123           |    [Santos][santos]     |                           |
| 클로저 활용 사례           | 콜백 함수 내부에서 외부 데이터를 사용하고자 할 때 |           125           |     [Local][local]      |                           |
|                            | 접근 권한 제어(정보 은닉)                         |           129           |     [Local][local]      |                           |
|                            | 부분 적용 함수                                    |           134           |     [Local][local]      |                           |
|                            | 커링 함수                                         |           141           |     [Local][local]      |                           |
| 정리                       | 정리                                              |           145           |     [Local][local]      |                           |

<br>
<br>

**06장. 프로토타입** 🤩

| <center>큰 제목</center> | <center>작은 제목</center>       | <center>페이지</center> | <center>작성자</center> | <center>완료여부</center> |
| ------------------------ | -------------------------------- | :---------------------: | :---------------------: | :-----------------------: |
| 프로토타입의 개념 이해   | constructor, prototype, instance |           147           |    [Santos][santos]     |                           |
|                          | constructor 프로퍼티             |           157           |    [Santos][santos]     |                           |
| 프로토타입 체인          | 메서드 오버라이드                |           160           |     [Local][local]      |                           |
|                          | 프로토타입 체인                  |           162           |     [Local][local]      |                           |
|                          | 객체 전용 메서드의 예외사항      |           168           |     [Local][local]      |                           |
|                          | 다중 프로토타입 체인             |           171           |     [Local][local]      |                           |
| 정리                     | 정리                             |           173           |     [Local][local]      |                           |

<br>
<br>

**07장. 클래스** 🤩

| <center>큰 제목</center>      | <center>작은 제목</center>                       | <center>페이지</center> | <center>작성자</center> | <center>완료여부</center> |
| ----------------------------- | ------------------------------------------------ | :---------------------: | :---------------------: | :-----------------------: |
| 클래스와 인스턴스의 개념 이해 | 클래스와 인스턴스의 개념 이해                    |           175           |    [Santos][santos]     |                           |
| 자바스크립트의 클래스         | 자바스크립트의 클래스                            |           178           |    [Santos][santos]     |                           |
| 클래스 상속                   | 기본 구현                                        |           181           |     [Local][local]      |                           |
|                               | 클래스가 구체적인 데이터를 지니지 않게 하는 방법 |           189           |     [Local][local]      |                           |
|                               | constructor 복구하기                             |           193           |     [Local][local]      |                           |
|                               | 상위 클래스에의 접근 수단 제공                   |           195           |     [Local][local]      |                           |
| ES6의 클래스 및 클래스 상속   | ES6의 클래스 및 클래스 상속                      |           197           |    [Santos][santos]     |                           |
| 정리                          | 정리                                             |           200           |    [Santos][santos]     |                           |

<br>
<br>
<br>

## 3. Reference

- [코어자바스크립트][core-javascript]

[core-javascript]: https://www.aladin.co.kr/shop/wproduct.aspx?ISBN=K532636268&start=pnaver_02
[santos]: https://github.com/SangchoKim
[local]: https://github.com/blocallee
[데이터타입의종류]: ./contents/01.데이터타입/1.데이터타입의종류/1-1.데이터타입의종류.md
[메모리와데이터]: ./contents/01.데이터타입/2.데이터타입의관한배경지식/2-1.메모리와데이터.md
[식별자와변수]: ./contents/01.데이터타입/2.데이터타입의관한배경지식/2-2.식별자와변수.md
[변수선언]: ./contents/01.데이터타입/3.변수선언과데이터할당/3-1.변수선언.md
[데이터할당]: ./contents/01.데이터타입/3.변수선언과데이터할당/3-2.데이터할당.md
[불변값]: ./contents/01.데이터타입/4.기본형데이터와참조형데이터/4-1.불변값.md
[가변값]: ./contents/01.데이터타입/4.기본형데이터와참조형데이터/4-2.가변값.md
[변수복사비교]: ./contents/01.데이터타입/4.기본형데이터와참조형데이터/4-3.변수복사비교.md
[불변객체를만드는간단한방법]: ./contents/01.데이터타입/5.불변객체/5-1.불변객체를만드는간단한방법.md
[얕은복사와깊은복사]: ./contents/01.데이터타입/5.불변객체/5-2.얕은복사와깊은복사.md
[undefined와null]: ./contents/01.데이터타입/6.undefined와null/6-1.undefined와null.md
[정리]: ./contents/01.데이터타입/7.정리/7-1.정리.md
[컨텍스트this]: ./contents/02.실행컨텍스트/4.this/4-1.this.md
[컨텍스트정리]: ./contents/02.실행컨텍스트/5.정리/5-1.정리.md
[전역공간에서의this]: ./contents/03.this/1.상황에따라달라지는this/1-1.전역공간에서의this.md
[메서드로서호출할때그메서드내부에서의this]: ./contents/03.this/1.상황에따라달라지는this/1-2.메서드로서호출할때그메서드내부에서의this.md
[함수로서호출할때그메서드내부에서의this]: ./contents/03.this/1.상황에따라달라지는this/1-3.함수로서호출할때그함수내부에서의this.md
[콜백함수호출시그함수내부에서의this]: ./contents/03.this/1.상황에따라달라지는this/1-4.콜백함수호출시그함수내부에서의this.md
[생성자함수내부에서의this]: ./contents/03.this/1.상황에따라달라지는this/1-5.생성자함수내부에서의this.md
[콜백함수란]: ./contents/04.콜백함수/1.콜백함수란/1-1.콜백함수란.md
[호출시점]: ./contents/04.콜백함수/2.제어권/2-1.호출시점.md
