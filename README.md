<div align=center>
  <img width="400" height="120" alt="Image" src="https://github.com/user-attachments/assets/f08bd3ce-a210-415c-ab17-0e6252bc5f73" /><br>
  <h1>CorAi(Coordi+Ai) - 날씨 기반 맞춤형 코디 추천 서비스</h1>
</div>
<br>


## 목차
* 프로젝트소개
* 개발기간
* 기술스택
* ERD
* 담당기능
* 기능설명
<br>


## 프로젝트소개
<div>
  Gemini AI와 날씨 데이터를 결합하여 맞춤형 코디를 제안하고 내 옷장을 스마트하게 관리해주는 패션 비서 서비스입니다. <br>
매일 아침 "오늘 뭐 입지?" 고민 해결: 급변하는 날씨 속에서 매번 옷차림을 고민해야 하는 현대인의 번거로움을 해결하고<br>
외출 준비 시간을 줄여주는 실용적인 서비스를 만들고자 했습니다.
</div>
<br>


## 개발기간
26/03/03 ~ 26/03/27(4주)
<br><br>


## Tech Stacks
<div>
  <h4>Frontend</h4>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
</div>
<div>
  <h4>Backend</h4>
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/jpa-232F3E?style=for-the-badge&logo=jpa&logoColor=white"/>
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
</div>
<div>
  <h4>Database</h4>
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white"/>
</div> 
<div>
  <h4>Cloud</h4>
  <img src="https://img.shields.io/badge/ams%20rds-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
</div> 
<div>
  <h4>API</h4>
  <img src="https://img.shields.io/badge/google%20gemini-4285F4?style=for-the-badge&logo=google%20gemini&logoColor=white">
  <img src="https://img.shields.io/badge/OpenWeatherMap-FF6600?style=for-the-badge&logo=OpenWeatherMap&logoColor=white">
  <img src="https://img.shields.io/badge/Kakao-%23FFCD00.svg?style=for-the-badge&logo=kakao&logoColor=black">
  <img src="https://img.shields.io/badge/naver-03C75A?style=for-the-badge&logo=naver&logoColor=white">
  <img src="https://img.shields.io/badge/google-4285F4?style=for-the-badge&logo=google&logoColor=white">
</div>
<div>
  <h4>Tools</h4>
  <img src="https://img.shields.io/badge/Eclipse IDE-2C2255?style=for-the-badge&logo=eclipse-ide&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
</div>
<br>


## ERD
<img width="1337" height="941" alt="Image" src="https://github.com/user-attachments/assets/cf58978c-dda2-432e-9f94-b50a9e2ed14e" />
<br>


## 담당기능
<div>
  <h4>백진욱(팀장) : 코디 추천 로직</h4>
  <h4>김성주 : 관리자 기능 구현, 에러 로그 수집 및 모니터링 시스템 구축</h4>
  <h4>유지은 : 위치·날씨 기반 카테고리 추천 메인페이지 및 날씨 Redis 캐싱 구현, 코디 공유 게시판</h4>
  <h4>이태주 : 나의옷장, DB 및 AI 기반 오류 기록 수집/분석 및 관리</h4>
  <h4>임소희 : OAuth2 기반 소셜 로그인 및 JWT/Redis 보안 인증 체계 구현</h4>
</div>
<br>


## 기능설명
<div>
  <h4>1. 메인페이지</h4>
  <video src="https://github.com/user-attachments/assets/a4690f9f-ecf0-4a8f-a2c7-2d636a5b1ac0" controls width="100%"></video>
</div>
<div>
  <h4>2. 회원가입/로그인</h4>
  <video src="https://github.com/user-attachments/assets/3dc92c8d-b889-4a52-bf02-38a5a2349ed0" controls width="100%"></video>
</div>
<div>
  <h4>3. 코디 추천</h4>
  <video src="https://github.com/user-attachments/assets/70821050-aa05-4cfb-a0ef-51edf15f19a8" controls width="100%"></video>
</div>
<div>
  <h4>4. 나의옷장(프로필수정/코디 등록)</h4>
  <video src="https://github.com/user-attachments/assets/d259f3cd-7600-4287-8b79-e7b04b674224" controls width="100%"></video>
</div>
<div>
  <h4>5. 커뮤니티</h4>
  <video src="https://github.com/user-attachments/assets/4f0f2817-b3bc-4b86-9488-68f6c28dc78e" controls width="100%"></video>
</div>
<div>
  <h4>6. 관리자페이지</h4>
  <video src="https://github.com/user-attachments/assets/8fe3869d-8ab9-4f77-a9d7-45f1caf0a06c" controls width="100%"></video>
</div>
<div>
  <h4>7. 에러로그관리</h4>
  <video src="https://github.com/user-attachments/assets/af6aa042-97ea-4250-8a41-d253bedfdea7" controls width="100%"></video>
</div>

