## 김스캇과 함께하는 풀스택 개발자 부트캠프 (Nest.js & Next.js in TypeScript)



### Concept 1 : 시작하기 전에

1. 개발 스택(Development Stack)
   1. TypeScript v5
   2. Yarn Berry v3
   3. Jest v29
   4. Seq v2023
   5. Backend
      1. Nest.Js v9
      2. Prisma v4
      3. Mongo v6
      4. Redis v7
      5. Bull MQ v3
   6. Frontend
      1. Next.js v13
      2. React v18
      3. React Redux v8
      4. MUI v6
2. 개발 환경(Development Environment)
3. 개발 방법론(Development Methodology)
4. 객제 치향 프로그래밍(Object-Oriented Programming)
5. 테스트 주도 개발(Test Driven Development) 
6. 클린 아키텍쳐를 위한 SOLID 원칙(SOLID Principal for Clean Architecture)
7. 디자인 패턴(Design Pattern)
8. 마이크로 서비스 아키텍쳐(Micro-Service Architecture: MSA)
9. 패키지 관리(Package Management: Yarn Berry v3)
10. 모놀리식 저장소(Monolithic Repository)
11. 지속적 코드 통합 및 배포 자동화(Continues Integration & Continues Delivery: CI&CD)
    1. Docker
    2. Kubernetes
    3. GitHub Actions



## 실무에 필요한 사전 지식.

### Basic 1 : TypeScript

1. TypeScript를 왜 사용해야 하는가.
   1. TypeScript의 개요
   2. 정적 타입 언어와 동적 타입언어
2. Fundamentals
   1. 기본 타입(Basic Type)
      1. 타입스크립트의 타입(Type in TypeScript)
      2. 타입 어노테이션(Type Annotations)
      3. 타입 인터페이스(Type Interface)
      4. 숫자 타입(Number Type)
      5. 문자 타입(String Type)
      6. 불리언 타입(Boolean Type)
      7. 객체 타입(Object Type)
      8. 배열 타입(Array Type)
      9. 튜플 타입(Tuple Types)
      10. 열거 타입(Enum Types)
      11. 애니 타입(Any Type)
      12. 네버 타입(Never Type)
      13. 유니온 타입(Union Types)
      14. 타입 별칭(Type Aliases)
      15. 문자열 리터럴 타입(String Literal Types)
   2. 제어문 (Control Flow Statements)
      1. 조건문(if else)
      2. 제어문(switch case)
      3. 반복문(for)
      4. 반복문(while)
      5. 반복문(do while)
      6. 중단(break)
   3. 함수(Functions)
      1. 타입스크립트의 함수(Functions in TypeScript)
      2. 함수 타입(Function Type)
      3. 옵션 파라미터(Optional Parameters)
      4. 기본 파라미터(Default Parameters)
      5. 나머지 파라미터(Rest Parameters)
      6. 함수 오버로딩(Function Overloading)
   4. 클래스(Classes)
      1. 타입스크립트의 클래스(Classes in TypeScript)
      2. 제한 접근자(Access Modifiers)
      3. 읽기전용 속성(Read-only Properties)
      4. 상속(Inheritance)
      5. 정적 메서드와 속성(Static Method and Properties)
      6. 추상 클래스(Abstract Classes)
   5. 인터페이스(Interfaces)
      1. 타입스크립트의 인터페이스
      2. 확장 인터페이스(Extending Interfaces)
   6. 고급 타입(Advanced Types)
      1. 교차 타입(Intersection Types)
      2. 타입 가드(Type Guards)
      3. 타입 변환(Type Casting)
      4. 타입 어설션(Type Assertion)
      5. 타입 추론(Type Inference)
   7. 제네릭(Generics)
      1. 타입스크립트의 제네릭
      2. 제네릭 제약(Generic Constraints)
      3. 제네릭 인터페이스(Generic Interface)
      4. 제네릭 클래스(Generic Classes)

### Basic 3 : Jest

1. Jest 
   1. Jest 설치.
   2. 단위 테스트(Unit-Test)
   3. 끝점 테스트(E2E Test)
   4. 필수 문법
2. Code Coverage
3. Test Case
4. Test Scenario
5. Test Management

### Basic 2 : Nest.js

1. Nest.js의 소개
   1. Nest란 
   2. Nest설치
   3. Nest CLI
   4. 수명 주기(Life-Cycle)
   5. 의존성 주입(DI)
2. 모듈
3. 프로바이더
4. 서비스
5. 컨트롤러
6. 미들웨어
7. 파이프
8. 데코레이터
9. 인터셉터
10. 가드
11. 필터 
12. 스케쥴링
13. 테스트 자동화

### Basic 3 : NextJs

1. Next.js의 소개

   1. Next.js란
   2. 왜 사용해야 할까.

2. Next.js 시작하기

   1. 프로젝트 구조
   2. Babel, Webpack

3. 렌더링 전략

   1. SSR
   2. CSR
   3. SSG

4. 내장 컴포넌트

   1. 라우팅
   2. 정적 자원
   3. 메타 테이터 
   4. 레이아웃

5. 상태 관리

   1. Local 상태 관리
   2. Global 상태 관리
   3. Context
   4. Redux

6. UI 프레임워크

   1. MUI 프레임워크
   2. eMotion / Cache

7. SEO

8. 성능

9. 테스트 

   

### Basic 4 : Monolithic Repository 

1. GitHub 

2. Yarn Berry 구성. 

3. 개발 & 빌드 환경 구성.

4. 공용 프로젝트 구성.

5. Nest.js 프로젝트 구성

6. Next.js 프로젝트 구성

7. 테스트 프로젝트 구성

8. 배포 프로젝트 구성

   

### Basic 5 : CI & CD

1. Dockerize 
2. Kubernetes
3. Github Actions



## Part 1: 실무에서 사용하는 개발 환경

### Practice 1 : Repository

1. Monolithic Repository
2. 프로젝트 구성
3. IDE 설정
4. 빌드 환경 구성
5. 배포 환경 구성



## Part 2: 실무에서 사용하는 Forum 시스템

### Practice 1 : 설계 

1. 요구사항 정의 
2. 화면 설계
3. 테스트 시나리오
4. 아키텍쳐 설계
5. 비지니스 로직 설계
6. 클래스 설계
7. 데이터베이스 설계

### Practice 3 : Nest.js로 백엔드 개발

### Practice 4 : Next.js로 프론트엔드 개발

### Practice 4 : 배포 및 유지 관리 



## 

## Part 3: 실무에서 사용하는 인증/권한 시스템

### Practice 1 : 설계 

1. 요구사항 정의 
2. 화면 설계
3. 테스트 시나리오
4. 아키텍쳐 설계
5. 비지니스 로직 설계
6. 클래스 설계
7. 데이터베이스 설계

### Practice 3 : Nest.js로 백엔드 개발

### Practice 4 : Next.js로 프론트엔드 개발

### Practice 4 : 배포 및 유지 관리 



## Part 4: 실무에서 사용하는 eCommerce 시스템

### Practice 1 : 설계 

1. 요구사항 정의 
2. 화면 설계
3. 테스트 시나리오
4. 아키텍쳐 설계
5. 비지니스 로직 설계
6. 클래스 설계
7. 데이터베이스 설계

### Practice 3 : Nest.js로 백엔드 개발

### Practice 4 : Next.js로 프론트엔드 개발

### Practice 4 : 배포 및 유지 관리 



## Part 5: 실무에서 사용하는 입장권 예약 시스템

### Practice 1 : 설계 

1. 요구사항 정의 
2. 화면 설계
3. 테스트 시나리오
4. 아키텍쳐 설계
5. 비지니스 로직 설계
6. 클래스 설계
7. 데이터베이스 설계

### Practice 3 : Nest.js로 백엔드 개발

### Practice 4 : Next.js로 프론트엔드 개발

### Practice 4 : 배포 및 유지 관리 

