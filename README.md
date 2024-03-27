# 제준영 (202030329)


<!-- ------------------------------------------------------------------------- -->

## 2024년 3월 27일 수업 내용
[JSX란?](#jsx란)  
[엘리먼트란?](#엘리먼트란)  
[엘리먼트(리액트)의 생김새](#엘리먼트리액트의-생김새)  
[엘리먼트의 특증](#엘리먼트의-특증)  
[컴포넌트란?](#컴포넌트란)  
[Props란?](#props란)   
[pure 함수와 Impure 함수](#pure-함수와-impure-함수)  

### JSX란?
- 자바 스크립트와 XML를 합친 것
- 컴포넌트를 사용하지 위해 
- 내부 XML/HTML 코드를 자바스크립드로 변환 
- 가독성을 높여 주는 역할   
- JSX안에서 자바 스크립트문서를 사용하고 싶으면 {}안에다가 사용

#### JSX 장점 
- 코드의 간결
- 가독성 향상
- 보안이 강함

### 엘리먼트란?
- 리액트 앱을 구성하는 요소
- 리액트에서 가장 작은 빌딩 블럭들
- 웹사이트의 경우는 DOM 엘리먼트이며, HTML 요소   

#### 리액트 엘리먼트와 DOM 엘리먼트의 차이
- 리액트 엘리먼트는 Virtual DOM 의 형식으로 취함
    - 빠르다
- DOM 엘리먼트는 페이지의 모든 정보를 갖고 있음
    - 느리다

### 엘리먼트(리액트)의 생김새
- 자바스크립트 객체의 형태로 존재
- 마음대로 변경할 수 없는 불변성
- type 대신에 리액트 컴포넌트

### 엘리먼트의 특증
- 내용을 마음대로 변경할 수 없는 불변성20203

### 컴포넌트란?
- 리액트는 컴포넌트 기반의 구조
- 컴포넌트 재사용이 가능, 전체 코드랑을 줄일 수 있어서 개발시간 및 유지보수 비용 감소
- 자바스크립트 함수와 유사
- 입력은 Props가 담당하고 출력은  리액트 엘리먼트의 형태
- 객체 지향의 개념과 비슷

#### 컴포넌트 구조란
- 작은 컴포넌트가 모여 큰 컴포넌티, 큰 컴포넌트가 모여 전체 페이지

### Props란?
- 컴포넌트의 속성
- 어떤 속성,Props를 넣느냐에 따라 다른 엘리먼트 출력
- 다양한 정보를 담고 있는 자바스크립트 객체

#### Props의 특징
- 읽기 전용 
- 속성이 다른 엘리먼트를 생성하려면 새로운 Props 를 컴포넌드에 전달

### Pure 함수와 Impure 함수
- pure 함수는 인수로 받은 정보가 함수 내부에서 변하지 않는 함수
- Impure 함수는 인수로 받은 정보가 함수 내부에서 변하는 함수

<!-- ------------------------------------------------------------------------- -->

## 2024년 3월 20일 수업 내용
[리액트란?](#리액트란)

### 리액트란?
- 사용자 인터페이스를 만들기 위한 ~~자바스크립트~~ 라이브러리  
- SPA 를 쉽고 빠르게 만들 수 있도록 해주는 도구
- 복잡한 사이드를 쉽고 빠르게 만들고, 관리하기 위한 도구

#### 리액트의 장점
- Virtual DOM (비동기식) 방법으로 사용해서 속도가 빠르다 (필요한 부분만 수정)
- 컴포넌트를 조합해서 개발하여 재사용성이 뛰어나다
- 메타에서 오픈소스 프로젝트로 관리하고 있어 계속 발전
- 크로스 플랫폼 모바일 앱 개발 가능
- 활발한 지식 공유(커뮤니티 활성화)

#### 리액트의 단점
- ~~방대한 학습량~~(자바스크립도를 공부한 경우 빠르게 학습가능)
- ~~높은 상태 관리 복잡도~~(18버전 이후 라이브 사이클를 잘 사용 안함)
- 너무 빠른 발전

<!-- ------------------------------------------------------------------------- -->

## 204년 3월 13일 수업 내용

[HTML란?](#html란)  
[CSS란?](#css란)  
[자바스크립트](#자바스크립트란)

### HTML란?
- 웹 사이트의 구조(뻐대)
- 대부분 페어로 사용
- < 문법/ > = HTML문법(X)
- SPA(Single Page Application) Page는 하나지만 필요한 요소만 교체

### CSS란?
- 웹 사이트의 스타일 시트(살)
- 반응형에 적합
- 반응형 웹에 작업량을 줄이기 위해 Sass사용

### 자바스크립트란?
- 웹 사이트의 기능(머리)
- 정적인 사이트에서 동적인 사이트로 변화하기 위해 사용

#### 자바스크립트 자료형
- var - 중복 선언 가능, 재할당 가능
- let -  중복 선언 불가능, 재할당 가능
- const - 중복 선언 불가능, 재할당 불가능 (상수)
- Array type - 배열(배열에 모든 다 가능)
- Object type - 속성
- json - 안에 모든 가능 (json 안에 json 가능)
- 대입 연산자 - 대입(=)
- 산술 연산자 - 산술(*,-,+,/)
- 증감 연산자 - 증가 혹은 감소
- 비교 연산자 - 비교 (2개는 모양만, 3개는 정확한)
- 삼항 연산자 - 조건부 연산자 내용 참 거짓 3개를 사용(a?b:c)
- function - 일반적은 함수(function foo(x,y)) {return x+y}
- 화살표 함수 - let woo = (x,y) => {return x+y} 객체를 만들어서 사용

<!-- ------------------------------------------------------------------------- -->

## 2024년 3월 6일 수업 내용
[버전 관리](#버전-관리)

### 버전 관리
[유의적 버전](#유의적-버전)  
[사용법](#사용법-ex-3145)

#### 유의적 버전 
- 개발자가 사용하는 버전
- 호환을 위해 사용하는 버전 생성 방법

#### 사용법 (Ex: 3.14.5)
- 첫번째 자리는 배포한 번호(1.0.0)
- 두번째 자리는 기능을 추가한 번호(0.1.0)
- 마지막 자리는 오류를 수정한 번호(0.0.1)
- 앞 번호가 올라가면 뒤에 번호는 초기화
