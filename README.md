# JUnit 학습

## String 클래스 학습 테스트

### 요구사항 1

* "1,2"을 `,` 로 split 했을 때 1과 2로 잘 분리되는지 확인하는 학습 테스트를 구현한다.
* "1"을 `,` 로 split 했을 때 1만을 포함하는 배열이 반환되는지에 대한 학습 테스트를 구현한다.

> `study.StringSplitTest`

### 요구사항 2

* "(1,2)" 값이 주어졌을 때 `String`의 `substring()` 메소드를 활용해 `()` 을 제거하고 "1,2"를 반환 하도록 구현한다.

> `study.StringSubstringTest`

### 요구사항 3

* "abc" 값이 주어졌을 때 `String`의 `charAt()` 메소드를 활용해 특정 위치의 문자를 가져오는 학습 테스트를 구현한다.
* `String`의 `charAt()` 메소드를 활용해 특정 위치의 문자를 가져올 때 위치 값을 벗어나면 `StringIndexOutOfBoundsException`이 발생하는 부분에 대한 학습 테스트를 구현한다.
* `JUnit`의 `@DisplayName`을 활용해 테스트 메소드의 의도를 드러낸다.

> `study.StringCharAtTest`

## Set Collection 학습 테스트

### 요구사항 1

* Set의 size() 메소드를 활용해 Set의 크기를 확인하는 학습테스트를 구현한다.

### 요구사항 2

* Set의 contains() 메소드를 활용해 1, 2, 3의 값이 존재하는지를 확인하는 학습테스트를 구현하려한다.
* 구현하고 보니 다음과 같이 중복 코드가 계속해서 발생한다.
* JUnit의 ParameterizedTest를 활용해 중복 코드를 제거해 본다.

### 요구사항 3

* 요구사항 2는 contains 메소드 결과 값이 true인 경우만 테스트 가능하다. 입력 값에 따라 결과 값이 다른 경우에 대한 테스트도 가능하도록 구현한다.
* 예를 들어 1, 2, 3 값은 contains 메소드 실행결과 true, 4, 5 값을 넣으면 false 가 반환되는 테스트를 하나의 Test Case로 구현한다

# 숫자 야구 게임

## 진행 방법

* 숫자 야구 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 과제를 제출한다.

## 과제 제출 과정

* [과제 제출 방법](https://github.com/next-step/nextstep-docs/tree/master/precourse)
