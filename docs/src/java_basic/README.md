# 소개 및 목차

**자바 기본 개념**
<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F3ec27036-48db-4673-8d1f-f956723f81d8%2FUntitled.png?table=block&id=bb2c7856-8cd3-4b5a-8a2a-4f861fa5659d&spaceId=19df36b8-17d5-4912-a1cf-0874ad632855&width=2000&userId=71f91cc9-adf1-4eb7-ad36-c49e63ea8af4&cache=v2" style="margin: 30px 0">

---
**자바의 장점**
- 모든 운영체제에서 실행이 가능하다.
  - 자바로 작성된 프로그램은 운영체제와 상관없이 모두 실행되기 때문에 윈도우에서 개발된 프로그램을 맥OS나 리눅스에서 실행할 수 있다는 장점이 있다.
- 객체 지향 프로그래밍
  - 객체를 만들고 이 객체들을 연결해서 더 큰 프로그램을 완성시키는 기법을 객체 지향 프로그램이라 하고 자바는 OOP를 위한 최적의 언어이다.
- 메모리 자동 관리
  - 자바는 메모리를 자동 관리하므로, 개발자는 메모리 관리의 수고를 덜어 기능 개발에 집중할 수 있다.

**자바 가상머신**

바이트 코드 파일(~.class)을 특정 운영체제가 이해하는 기계어로 번역하고 실행시키는 명령어는 java이다. java 명령어는 JDK와 함께 설치된 JVM을 구동시켜 바이트 코드 파일을 완전한 기계어로 변역하고 실행시킨다.
바이트 코드 파일은 운영체제와 상관없이 모두 동일한 내용으로 생성되지만, JVM은 운영체제에서 이해하는 기계어로 번역해야 하므로 OS별로 다르게 설치된다. 그래서 운영체제 별로 설치하는 JDK가 다르다.

**자바 프로그램 개발 과정**
1. 소스 코드 작성
2. javac.exe로 바이트코드 파일을 생성(.class)
3. 바이트코드 파일(.class)  // bin 디렉토리에 패키지 디렉토리와 함께 저장된다. 
4. java.exe로 JVM을 구동시킨다.
5. 특정 os에서 동작하는 jvm을 구동하고 os에서 실행할 수 있는 기계어로 번역 후 main() 메소드를 찾아 메소드 블록을 실행시킨다.

---

#### 1.변수와 타입
  - [1-1.변수 선언](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_1)
  - [1-2.정수 타입](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/IntegerLiteral.java)
  - [1-3.문자 타입](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/StringLiteral.java)
  - [1-4.실수 타입](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/RealNumberLiteral.java)
  - [1.5.문자열 타입](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/StringLiteral.java)
  - [1.6.자동 타입 변환](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/AutoCasting.java)
  - [1.7.강제 타입 변환](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/ForcedTypeConversion.java)
  - [1.8.연산식에서 자동 타입 변환](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_1)
  - [1.9.문자열을 기본 타입으로 변환](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_1)
  - [1.10.콘솔로 변수 출력](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/ConsolePrint.java)
  - [1.11.키보드 입력 데이터를 변수에 저장](https://github.com/ithingv34/Reading/blob/thisIsJava/thisIsJava/Chapter_1/src/ScannerVariable.java)

---

#### 2. 연산자
  - [2.1. 부호/증감 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.2. 산술 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.3. 오버플로우와 언더플로우](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.4. 정확한 계산은 정수 연산으로](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.5. 나눗셈 연산 후 Nan과 Infinity 처리](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.6. 비교 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.7. 논리 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)
  - [2.8. 비트 논리 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2/src/BitLogic.java)
  - [2.9. 비트 이동 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2/src/BitShift.java)
  - [2.10. 삼항 연산자](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_2)

---

#### 3. 조건문과 반복문
  - [3-1. switch 문](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_3/src/Switch.java)
    - [3-1-1. Java 12 버전 이후](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_3) 
  - [3-2. do-while 문](https://github.com/ithingv34/Reading/tree/thisIsJava/thisIsJava/Chapter_3)

---

#### 객체지향 프로그래밍

**참조타입**
  - [데이터 타입 분류]()
  - [메모리 사용 영역]()
  - [참조 타입 변수의 ==, != 연산]()
  - [null 과 NullPointerException]()
  - [문자열(String) 타입]()
  - [배열(Array) 타입]()
  - [다차원 배열]()
  - [객체를 참조하는 배열]()
  - [객체를 참조하는 배열]()
  - [배열 복사]()
  - [배열 항목 반복을 위한 향상된 for 문]()
  - [main() 메소드의 String매개변수 용도]()
  - [Enum 타입]()

**클래스**
  - [클래스 선언]()
  - [객체 생성과 클래스 변수]()
  - [클래스의 구성 멤버]()
  - [필드 선언과 사용]()
  - [생성자 선언과 호출]()
  - [메소드 선언과 호출]()
  - [인스턴스 멤버]()
  - [정적 멤버]()
  - [final 필드와 상수]()
  - [패키지]()
  - [접근 제한자]()
  - [Getter, Setter]()
  - [싱글톤 패턴]()

**상속**
  - [상속 개념]()
  - [클래스 상속]()
  - [부모 생성자 호출]()
  - [메소드 오버라이딩]()
  - [final 클래스와 final 메소드]()
  - [protected 접근 제한자]()
  - [타입 변환]()
  - [다형성]()
  - [객체 타입 확인]()
  - [추상 클래스]()
  - [봉인된 클래스]()

**인터페이스**
  - [인터페이스 역할]()
  - [상수 필드]()
  - [추상 메소드]()
  - [디폴트 메소드]()
  - [정적 메소드]()
  - [private 메소드]()
  - [다중 인터페이스 구현]()
  - [인터페이스 상속]()
  - [타입 변환]()
  - [다형성]()
  - [객체 타입 확인]()
  - [봉인된 인터페이스]()

---

#### 중첩 선언과 익명 객체
  - [중첩 클래스]()
  - [인스턴스 멤버 클래스]()
  - [정적 멤버 클래스]()
  - [로컬 클래스]()
  - [바깥 멤버 접근]()
  - [중첩 인터페이스]()
  - [익명 객체]()

---
#### 라이브러리와 모듈
  - [라이브러리]()
  - [모듈]()
  - [응용프로그램 모듈화]()
  - [모듈 배포용 JAR 파일]()
  - [패키지 은닉]()
  - [전이 의존]()
  - [집합 모듈]()
  - [리플렉션 허용]()
  - [자바 표준 모듈]()

---
#### 예외 처리
  - [예외와 예외 클래스]()
  - [예외 처리 코드]()
  - [예외 종류에 따른 처리]()
  - [리소스 자동 닫기]()
  - [예외 던지기]()
  - [사용자 정의 예외]()

---
#### 자바 라이브러리 활용
  - [API 문서]()
  - [java.base 모듈]()
  - [Object 클래스]()
  - [System 클래스]()
  - [문자열 클래스]()
  - [Wrapper 클래스]()
  - [수학 클래스]()
  - [날짜와 시간 클래스]()
  - [형식 클래스]()
  - [정규 표현식 클래스]()
  - [리플렉션]()
  - [어노테이션]()

---
#### 제네릭
  - [제네릭 타입]()
  - [제네릭 메소드]()
  - [제한된 타입 파라미터]()
  - [와일드카드 타입 파라미터]()

---
#### 멀티 스레드
  - [멀티 스레드 개념]()
  - [메인 스레드]()
  - [작업 스레드 생성과 실행]()
  - [스레드 이름]()
  - [스레드 상태]()
  - [스레드 동기화]()
  - [스레드 안전 종료]()
  - [데몬 스레드]()
  - [스레드 풀]()

---
#### 컬렉션 자료구조
  - [컬렉션 프레임워크]()
  - [List 컬렉션]()
  - [Set 컬렉션]()
  - [Map 컬렉션]()
  - [검색 기능을 강화한 컬렉션]()
  - [LIFO와 FIFO 컬렉션]()
  - [동기화된 컬렉션]()
  - [수정할 수 없는 컬렉션]()

---
#### 람다식
  - [매개변수가 없는 람다식]()
  - [매개변수가 있는 람다식]()
  - [리턴값이 있는 람다식]()
  - [메소드 참조]()
  - [생성자 참조]()

---
#### 스트림 요소 처리
  - [내부 반복자]()
  - [중간 처리와 최종 처리]()
  - [리소스로부터 스트림 얻기]()
  - [필터링]()
  - [매핑]()
  - [정렬]()
  - [요소를 하나씩 처리]()
  - [요소 조건 만족 여부]()
  - [요소 기본 집계]()
  - [요소 커스텀 집계]()
  - [요소 수집]()
  - [요소 병렬 처리]()

----
#### 데이터 입출력
  - [입출력 스트림]()
  - [바이트 출력 스트림]()
  - [바이트 입력 스트림]()
  - [문자 입출력 스트림]()
  - [보조 스트림]()
  - [문자 변환 스트림]()
  - [성능 향상 스트림]()
  - [기본 타입 스트림]()
  - [프린트 스트림]()
  - [객체 스트림]()
  - [File과 Files 클래스]()

----
#### 네트워크 입출력
  - [IP 주소 얻기]()
  - [TCP 네트워킹]()
  - [UDP 네트워킹]()
  - [서버의 동시 요청 처리]()
  - [JSON 데이터 형식]()
  - [TCP 채팅 프로그램]()

----
#### 데이터베이스 입출력
  - [JDBC 개요]()
  - [DBMS 설치]()
  - [Client Tool 설치]()
  - [DB 구성]()
  - [DB 연결]()
  - [데이터 저장]()
  - [데이터 수정]()
  - [데이터 읽기]()
  - [프로시저와 함수 호출]()
  - [트랜잭션 처리]()
  - [게시판 구현]()