# Spring Auth

Spring Boot와 Spring Framework의 핵심 개념을 학습하기 위한 프로젝트입니다.

Bean 등록, 의존성 주입(DI), Spring Container, PasswordEncoder 사용법 등을 실습하며 Spring의 동작 원리를 이해하는 것을 목표로 개발하였습니다.

---

# 프로젝트 소개

Spring Framework의 핵심 기능인 IoC(Inversion of Control)와 DI(Dependency Injection)를 중심으로 학습한 프로젝트입니다.

`@Component`, `@Autowired`, `@Primary`, `@Qualifier` 등을 활용하여 Bean 관리 방식을 실습하였으며, `PasswordEncoder`를 이용한 비밀번호 암호화와 JUnit 테스트를 통해 Spring Boot의 기본 개발 환경을 익혔습니다.

---

# 기술 스택

* Java 21
* Spring Boot
* Spring Framework
* Spring Security
* Gradle
* JUnit 5

---

# 프로젝트 구조

```text
src
 ├── config
 ├── food
 ├── test
 └── resources
```

---

# 학습 내용

* Spring Boot 프로젝트 구성
* IoC(Inversion of Control)
* DI(Dependency Injection)
* Spring Bean 등록
* `@Component`
* `@Autowired`
* `@Primary`
* `@Qualifier`
* `PasswordEncoder`
* JUnit 테스트

---

# 주요 실습

## Bean 등록

* `@Component`를 이용한 Bean 등록

## 의존성 주입

* `@Autowired`
* `@Primary`
* `@Qualifier`

우선순위에 따른 Bean 주입 방식을 실습하였습니다.

## PasswordEncoder

Spring Security의 `PasswordEncoder`를 이용하여 비밀번호 암호화를 학습하였습니다.

## 테스트 코드

JUnit을 활용하여 Bean 등록과 의존성 주입이 정상적으로 동작하는지 확인하였습니다.

---

# 실행 방법

```bash
./gradlew bootRun
```

또는 IntelliJ IDEA에서 실행할 수 있습니다.

---

# 프로젝트 목적

Spring Boot의 핵심 개념인 IoC, DI, Bean 관리 방식을 이해하고, Spring Security의 PasswordEncoder와 테스트 코드를 직접 구현하며 Spring Framework의 기본 동작 원리를 학습하기 위한 프로젝트입니다.
