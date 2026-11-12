# 👋 Hi, I'm Brandon(김상준)

**Java 백엔드 개발자를 준비하고 있습니다.**

영어영문학과로 입학해 컴퓨터공학과로 전과했고, 졸업 후 호주에서 2년 넘게 워킹홀리데이를 했습니다.
DB 설계와 Spring MVC 백엔드를 중심으로 공부하고 있고, 호주에서 겪은 불편을 AI로 직접 서비스로 만들어 운영하고 있습니다.

- 🚀 **쌍용교육센터** Java Full-Stack 개발자 과정 · 2026.07 - 2026.12 (수료 예정)
- 🌏 **호주 워킹홀리데이** · 2024.03 - 2026.06
- 🎓 **한림대학교** 컴퓨터공학과 졸업 · 2018.03 - 2024.02 (영어영문학과 입학 후 전과)

&nbsp;

## 🤖 AI로 만든 서비스

### 🇦🇺 [워홀 88 — 세컨·서드 비자 근무 일수 카운터](https://github.com/kddong991121/whv-tracker)
<sub>개인 프로젝트 · 2026.11 출시, 운영 중 · [whv88.duckdns.org](https://whv88.duckdns.org)</sub>

호주 워홀 때 "이 근무가 비자 일수로 며칠 인정되지?"를 매번 직접 계산해야 했던 불편을 서비스로 만들었습니다.
**코드는 AI(Claude Code)가 작성했고**, 저는 기획·규칙 정리·테스트·배포·운영을 맡았습니다.

- 호주 내무부 공식 자료를 근거로 인정 일수 계산 규칙과 기획서(PRD)를 직접 정리
- 실제 페이슬립 4종으로 결과를 확인하며 AI에게 수정을 요청해 자동 입력 정확도를 맞춤
- 운영 로그에서 오류(탈퇴 요청 Deadlock, 배포 때마다 전원 로그아웃)를 발견하고 AI와 원인을 찾아 수정
- 출시 이틀 만에 **가입 22명** (워홀 커뮤니티 공유) · 운영비 **월 0원**

&nbsp;

## 📂 Projects

### 🏢 [이음 — 사내 그룹웨어 + IT 지원 통합](https://github.com/fds213/Spring_Project_1)
<sub>`Spring MVC` `MyBatis` `Oracle` `JSP` · 7인 팀 프로젝트 · 2026.10 - 2026.11</sub>

- 전자결재·근태 등 그룹웨어 기능과 IT 지원(티켓·자산)을 한 서비스로 묶은 팀 프로젝트
- 담당: 직원 가입·승인(사번 발급, 인원 한도), 사원 관리(부서·직급, 퇴사 처리, 조직도), 로그인·인증(5회 실패 잠금, 역할 변경 시 세션 종료)
- 커밋 88개, PR 37개 병합, PR 리뷰 33건 (2026.11 기준)
- 시스템 아키텍처 구성도 작성

### 🏫 [교육센터 관리 시스템 DB](https://github.com/kddong991121/edu-center-db)
<sub>`Oracle` `PL/SQL` `ERD` · 5인 팀 프로젝트 (조장) · 2026.08</sub>

- 24개 테이블 DB 설계, 출결 113,176건 등 더미 데이터 생성
- 인덱스 · 뷰 · 함수 · 프로시저 등 DB 오브젝트 구현
- 복합 인덱스로 기간별 출결 조회 **Cost 124 → 2**
- 버전 컬럼 기반 **낙관적 락으로 Lost Update 해결**

### 🍔 [맥도날드 통합 주문 웹](https://github.com/kddong991121/mcdonalds-order-web)
<sub>`React` `Vite` `JavaScript` · 5인 팀 프로젝트 · 2026.09</sub>

- 프로젝트 주제 제안
- 메뉴 목록 · 페이지네이션, 메뉴 상세(단품/세트 · 사이드 · 음료 · 재료 옵션) 화면 담당
- 옵션 선택에 따른 실시간 가격 계산과 장바구니 연결

### 📝 [Spring Memo](https://github.com/kddong991121/spring-memo)
<sub>`Spring MVC` `MyBatis` `Oracle` `JSP` · 개인 프로젝트 · 2026.10</sub>

- Controller → Service → DAO → Mapper 계층을 직접 구성한 카드형 메모장 CRUD
- 카테고리 테이블 JOIN으로 메모별 카테고리 색상 표시, 오늘/이전 메모 날짜 표시 분기
- HikariCP · SqlSessionTemplate 기반 MyBatis 연동, DB 접속 정보를 `properties`로 분리

<details>
<summary><b>이전 프로젝트 더 보기</b></summary>

&nbsp;

| 프로젝트 | 설명 | 기술 |
| :--- | :--- | :--- |
| [탁구 점수 관리 프로그램](https://github.com/kddong991121/TableTennis_Score_Program) | 듀스·서브권 교체·3판 2선승/5판 3선승 규칙을 반영한 콘솔 프로그램 (3인 팀, 2026.08) | `Java` |
| [웹 서버 기말 프로젝트](https://github.com/kddong991121/Web_final_project) | 세션 기반 회원 인증과 CRUD 게시판 웹 애플리케이션 | `JSP` `JDBC` `Tomcat` |
| [JSP 게시판](https://github.com/kddong991121/JSPBook) | Bootstrap 기반 게시판 (페이징, 아이디 중복 확인) | `JSP` `MySQL` `Bootstrap` |
| [스마트 포트폴리오](https://github.com/kddong991121/Android_final_project) | Lottie 애니메이션과 Expandable RecyclerView를 활용한 안드로이드 앱 | `Android` `Kotlin` `Java` |

</details>

&nbsp;

## 🛠 Tech Stack

### Backend & Database
<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/JSP-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_MVC-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/MyBatis-DC382D?style=flat-square" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square" />
  <img src="https://img.shields.io/badge/PL%2FSQL-336791?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

### Frontend & Mobile
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
</p>

### Learning Now
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

### Tools & AI
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipseide&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/DataGrip-000000?style=flat-square&logo=datagrip&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-D97706?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/ChatGPT-74AA9C?style=flat-square" />
</p>

<sub>팀 프로젝트에서는 Claude Code로 코드를 함께 작성하고 직접 검토했고, 워홀 88은 코드 작성을 AI에 맡기고 기획·검증·운영을 맡았습니다.</sub>

&nbsp;

## 📫 Contact

<p>
  <a href="mailto:kddong99@gmail.com"><img src="https://img.shields.io/badge/Gmail-kddong99@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>
