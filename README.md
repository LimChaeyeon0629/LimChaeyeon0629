## 🐾 Git Animals

<a href="https://github.com/devxb/gitanimals">
  <img
    src="https://render.gitanimals.org/farms/LimChaeyeon0629"
    width="600"
  />
</a>

<br>

# 👋 Hi, I'm Chaeyeon

### 사용자 화면부터 DB 저장까지, 전체 흐름을 연결하는 Full-Stack Developer

```text
기능을 단순히 동작하고 구현하는 것에서 그치지 않고,
실제 운영 상황에서 발생할 수 있는 문제를 고민하는 개발자를 지향합니다.
```

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

제가 담당한 파트는 **사용자 신고 및 관리자 신고 처리 시스템**입니다.

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
