# 👋 Hi, I'm Chaeyeon

### 사용자 화면부터 DB 저장까지, 전체 흐름을 연결하는 Full-Stack Developer

기능을 단순히 **“동작하게 만드는 것”**에서 끝내기보다,
화면에서 발생한 요청이 **API → Service → Database**까지 어떻게 흐르는지 이해하고
실제 운영 환경에서 발생할 수 있는 문제까지 고민하며 개발하고 있습니다.

특히 오류가 발생했을 때 추측으로 해결하기보다
**로그와 데이터 흐름을 따라 원인을 끝까지 추적하는 과정**을 중요하게 생각합니다.

<br>

## 🧑‍💻 About Me

* Java / Spring Boot 기반의 **Backend 개발**
* React / Next.js 기반의 **Frontend 개발**
* REST API 설계 및 Frontend ↔ Backend 연동
* Oracle / MySQL 기반 데이터 모델링 및 SQL
* JWT / Spring Security 기반 인증·인가
* Redis를 활용한 동시성 제어
* AWS EC2 / Nginx / Docker 기반 서비스 배포
* OpenAI API를 활용한 AI 기능 구현 경험
* Git / GitHub 기반 팀 프로젝트 협업 경험

<br>

## 🛠 Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge\&logo=springboot\&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge\&logo=springsecurity\&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge\&logo=hibernate\&logoColor=white)

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge\&logo=nextdotjs\&logoColor=white)
![Redux](https://img.shields.io/badge/Redux--Saga-764ABC?style=for-the-badge\&logo=redux\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)

### Database & Cache

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge\&logo=oracle\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white)

### Infra & Deployment

![AWS](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge\&logo=amazonec2\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge\&logo=nginx\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge\&logo=postman\&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge\&logo=swagger\&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge\&logo=figma\&logoColor=white)

<br>

## 🚀 Featured Project

### MOIT — 모임 플랫폼

> 모임 생성부터 참여, 리뷰, 신고 및 관리자 운영 기능을 제공하는 웹 서비스

**Tech Stack**
`Spring Boot` `Java` `React` `Next.js` `Oracle` `Redis` `JWT` `AWS` `Docker` `Nginx`

#### 🙋 My Contribution

제가 담당한 영역은 **사용자 신고 및 관리자 신고 처리 시스템**입니다.

* 사용자 신고 CRUD
* 관리자 신고 검색 / 페이징 / 승인 / 반려
* Spring Security + JWT 기반 사용자 / 관리자 권한 분리
* SecurityContext 기반 인증 사용자 식별 및 IDOR 방지
* Redis Lock 기반 중복 처리 방지
* 신고 승인 시 회원 신뢰도 점수 연동
* 관리자 처리 이력 Audit Log 저장
* `@TransactionalEventListener(AFTER_COMMIT)` + `@Async` 기반 이메일 발송
* OpenAI API 기반 신고 내용 작성 및 관리자 판단 보조
* AWS EC2 / Nginx / Docker / PM2 기반 서비스 배포

🔗 **Repository**
https://github.com/LimChaeyeon0629/moitreport

🌐 **Deployment**
https://moitreport.duckdns.org/

<br>

## 🔍 What I Care About

```text
"왜 동작하지?"에서 멈추지 않고,
"어디에서 데이터 흐름이 끊겼지?"를 찾는 개발자가 되고 싶습니다.
```

화면에서 값이 다르게 보이는 문제가 발생하면 데이터 흐름을 추적하며 문제의 범위를 좁혀갑니다.

또한 기능 구현 이후에도

`중복 요청` · `동시 처리` · `권한 검증` · `데이터 정합성` · `외부 API 장애`

와 같은 실제 운영 상황에서 발생할 수 있는 문제를 고민합니다.

<br>

## 📚 Currently Learning

* Java & Spring Boot Architecture
* REST API Design
* Database / SQL Optimization
* Authentication & Authorization
* Concurrency Control
* AWS & Docker Deployment
* Python
* AI / LLM API Integration

<br>

## 📊 GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=LimChaeyeon0629\&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LimChaeyeon0629\&layout=compact)

<br>

## 🐾 Git Animals

<a href="https://github.com/devxb/gitanimals">
  <img
    src="https://render.gitanimals.org/farms/LimChaeyeon0629"
    width="600"
  />
</a>
