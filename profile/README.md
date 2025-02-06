# 🩸🐶 반려견 헌혈 예약 웹사이트 DogHeroes 

## 📌 프로젝트 개요  
반려견의 헌혈 문화를 활성화하고, 견주들이 손쉽게 헌혈을 예약할 수 있도록 돕고 관리자가 손쉽게 예약 관리를 할 수 있는 웹 플랫폼입니다.  
헌혈 가능 병원 검색, 예약 신청, 긴급 헌혈 요청 등의 기능을 제공합니다.

## 🚀 주요 기능  
- 🐶 **회원가입 및 로그인** (JWT 기반 인증)  
- 📅 **헌혈 예약 시스템** (날짜 및 시간 선택)  
- 🔔 **긴급 헌혈 요청 및 알림 기능**  
- 🏥 **헌혈 병원 및 예약 일정 관리**  
- 📊 **헌혈 내역 제공**  

## 🛠️ 기술 스택  
### 📌 **Backend**  
- Spring Boot (Java)  
- Spring Security (JWT)  
- JPA (MySQL)  
- Docker, Jenkins (CI/CD)  

### 📌 **Frontend**  
- React (PWA 지원)  
- TailwindCSS  
- Axios (API 연동)  

### 📌 **DevOps**  
- GitHub Actions + Jenkins  
- Docker Compose  
- AWS (EC2, RDS, S3)  

## 🏗️ 프로젝트 구조  
```shell
📂 backend
 ┣ 📂 src/main/java/com/project
 ┃ ┣ 📂 domain  # DDD 기반 도메인 설계
 ┃ ┣ 📂 service # 핵심 비즈니스 로직
 ┃ ┣ 📂 controller # API 엔드포인트
 ┃ ┗ 📂 repository # 데이터 접근 레이어

📂 frontend
 ┣ 📂 src
 ┃ ┣ 📂 components  # 재사용 가능한 UI 요소
 ┃ ┣ 📂 pages       # 주요 화면 구성
 ┃ ┣ 📂 hooks       # 커스텀 훅 관리
 ┃ ┗ 📂 utils       # 공통 유틸 함수
