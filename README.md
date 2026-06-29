# Spring Auth

Spring Boot와 Spring Security를 활용하여 인증(Authentication)과 JWT(JSON Web Token) 기반 로그인 기능을 학습한 프로젝트입니다.

Spring Bean 관리, 의존성 주입(DI), PasswordEncoder를 이용한 비밀번호 암호화, JWT 생성 및 검증 과정을 구현하며 Spring Security의 핵심 개념을 익히는 것을 목표로 개발하였습니다.

---

# 프로젝트 소개

Spring Framework와 Spring Security의 핵심 기능을 실습하기 위해 개발한 프로젝트입니다.

Bean 등록과 의존성 주입, `PasswordEncoder`를 활용한 비밀번호 암호화, JWT 토큰 생성 및 검증 기능을 구현하였으며, 인증(Authentication)과 권한(Role) 관리의 기본 구조를 학습하였습니다.

---

# 기술 스택

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* JWT (jjwt)
* Gradle
* Lombok
* JUnit 5
* IntelliJ IDEA

---

# 프로젝트 구조

```text
src
 ├── auth
 ├── config
 ├── entity
 ├── food
 ├── jwt
 ├── resources
 └── test
```

---

# 주요 기능

## Spring Bean 관리

* `@Component`
* `@Autowired`
* `@Primary`
* `@Qualifier`

Bean 등록과 의존성 주입 방식을 실습하였습니다.

---

## PasswordEncoder

* 비밀번호 암호화
* BCryptPasswordEncoder 사용

Spring Security의 PasswordEncoder를 이용하여 안전한 비밀번호 저장 방식을 학습하였습니다.

---

## JWT 인증

* Access Token 생성
* JWT 검증
* 사용자 권한(Role) 정보 저장
* 토큰 만료 시간 설정

JWT 기반 인증 흐름을 구현하고 토큰을 이용한 사용자 인증 방식을 학습하였습니다.

---

## 권한(Role) 관리

* UserRoleEnum을 이용한 사용자 권한 관리
* ROLE_USER
* ROLE_ADMIN

권한 정보를 토큰에 포함하여 인증 및 인가 구조를 학습하였습니다.

---

# 학습 내용

* Spring Boot 프로젝트 구성
* IoC(Inversion of Control)
* DI(Dependency Injection)
* Spring Bean 관리
* PasswordEncoder
* Spring Security 기초
* JWT(JSON Web Token)
* 사용자 권한(Role) 관리
* 테스트 코드 작성

---

# 실행 방법

### 프로젝트 실행

```bash
git clone https://github.com/yonghyun0325/spring-auth.git

cd spring-auth

./gradlew bootRun
```

또는 IntelliJ IDEA에서 실행할 수 있습니다.

---

# 향후 개선 사항

* Refresh Token 적용
* 로그인 API 구현
* 회원가입 기능
* 예외 처리(Global Exception Handler)
* Validation 적용
* Swagger(OpenAPI) 적용
* 테스트 코드 확장

---

# 프로젝트 목적

Spring Boot와 Spring Security를 활용하여 인증(Authentication)과 인가(Authorization)의 기본 개념을 이해하고, JWT를 이용한 토큰 기반 인증 방식을 구현하기 위해 개발한 프로젝트입니다. 또한 Bean 관리, 의존성 주입, PasswordEncoder를 직접 적용하며 Spring Framework의 핵심 동작 원리를 학습하는 것을 목표로 하였습니다.
