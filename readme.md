# HelloServlet 프로젝트 기술 스택

이 문서는 현재 프로젝트에서 사용 중인 핵심 기술 스택을 정리한 내용입니다.

## 언어 / 런타임
- **Java 17**

## 웹 기술
- **Jakarta Servlet 5.0** (`jakarta.servlet-api:5.0.0`)
- **Servlet 기반 웹 애플리케이션** (`HttpServlet`, `web.xml` 매핑)

## 빌드 / 패키징
- **Apache Maven**
- 패키징 타입: **WAR** (`<packaging>war</packaging>`)
- Maven Compiler Plugin **3.11.0**
- Maven WAR Plugin **3.4.0**

## 배포 대상(호환)
- **Tomcat 10.x 이상** (Jakarta EE 9+ 네임스페이스 기준)

## 프로젝트 구조(요약)
- `src/main/java` : 서블릿 Java 소스
- `src/main/webapp` : 웹 리소스 및 `WEB-INF/web.xml`
- `pom.xml` : 의존성 및 빌드 설정
