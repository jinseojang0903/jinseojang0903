<h1 align="center">장진서 👋</h1>
<h3 align="center">일단 해보고 배우는 백엔드 개발자 · ERP와 데이터에 관심이 많습니다</h3>

---

### 🙋 About Me

- 🎓 명지대학교 정보통신공학과 (2027.02 졸업 예정)
- 💼 영림원소프트랩 기반기술연구소 웹WG 인턴 (2026.08 – 현재)
- 🌱 요즘 공부하는 것: C#/.NET, Blazor, Dapper, SQL, ADSP & SQLD
- 📜 정보처리기사
- 📫 jinseojang4@gmail.com

---

### 🛠 Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Backend & Data**

![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-5C2D91?style=flat-square&logo=blazor&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-ORM-A31515?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**AI & Tools**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### 💼 Experience

**영림원소프트랩 기반기술연구소 웹WG** · 인턴 · 2026.08 – 현재

- ERP 신제품 웹 개발과 기존 제품 리뉴얼 참여
- 신제품 웹 아키텍처 수립을 위한 기술 스터디, 테스트 기반 검증으로 아키텍처 고도화

**영림원소프트랩** · 신입 실무 교육 · 2026.01 – 2026.02

- ERP 개발자 입문 과정 수료 (304시간)
- ERP 업무 화면 구현 실습, SQL 기반 데이터 조회·처리, 회계 기초 학습

---

### 🏆 Projects

#### 🚌 [만차예보 · 양주 광역버스 만차 예보 AI](https://github.com/Yangju-AI-11/yangju-bus-forecast) · 팀 탈수있조

> 🥇 2026 양주시 미래인재 AI 공모전 **최우수상** (2026년 10월, 주제: 똑똑하고 편리한 양주)

광역버스가 **내 정류장에 도착할 때 빈자리가 없을 위험**을 과거 유사 운행의 실제 결과('n회 중 k회')로 예보하고, 도착 마감에 맞는 대안 버스를 비교해 주는 모바일 웹 서비스입니다. 양주시 광역버스 G1300·1306 노선, 덕현초교 정류장, 평일 출근 시간대를 대상으로 실증했습니다.

**맡은 역할: 백엔드 · 데이터 수집기 · 프론트엔드 구성**

- 경기버스정보(GBIS) 공공 API 실시간 수집기 구현 — 양주 광역 12개 노선의 위치·도착 정보를 노선별 독립 작업자가 10~40초 주기로 수집하고, 일일 호출 한도 검사·원본 JSONL 저장·수집 상태 리포트 처리
- 수집 데이터로 운행편을 재구성하고 '도착 시 0석' 정답 라벨 생성 (엄격·완화 등급, 미확인 사유 분류)
- FastAPI 기반 예보 스냅샷·정류장 조회·헬스체크 API와 PostgreSQL(Supabase) 테이블 설계
- React + Vite + TypeScript 모바일 웹 프론트엔드 구성 (조건 입력·예보 결과·근거 부족 화면)
- 수집기 systemd 서비스 배포(Oracle Cloud ARM), pytest·ruff 기반 테스트·린트 환경 구성

`Python` `FastAPI` `PostgreSQL` `Supabase` `React` `Vite` `TypeScript` `GBIS 공공데이터 API` `uv` `systemd`

#### ❄️ [스스로 학습하는 제설 AI 웹](https://github.com/jinseojang0903/CapstoneDesign) · 캡스톤디자인

> 🏅 명지대학교 IC-PBL 경진대회 수상 (2025년 2학기)

공공데이터로 서울시 도로의 결빙지수를 산출하고, 결빙 위험 구간을 피하는 안전 경로와 강화학습 기반 제설 경로를 추천하는 웹 서비스입니다.

**맡은 역할: 팀장 · 백엔드 · 데이터 수집 및 전처리 · AI 학습**

- 공공데이터를 수집·전처리해 경사, 결빙 취약 구간, 사고 이력, 유동 인구 기반의 도로별 결빙지수 산출
- 결빙 사고 데이터가 57건뿐인 한계를 가중치 기준 재설계로 보완
- PostgreSQL·PostGIS DB 설계, Flask RESTful API와 JWT 인증 구현
- OSMnx/NetworkX 도로망 그래프에 결빙지수를 매핑한 안전 경로 탐색
- Q-learning 강화학습으로 제설 경로 추천 모델 학습

`Python` `Flask` `PostgreSQL` `PostGIS` `OSMnx` `NetworkX` `Q-learning` `React` `Leaflet`

#### 🌱 Farmunity · 농업 커뮤니티 웹 서비스

> 🏅 명지대학교 창의적 SW프로그램 경진대회 수상 (2025년 2학기)

농사일지, 작물 일정 관리, 커뮤니티 게시판, 병해충 진단을 한곳에 모은 농업 커뮤니티 웹 서비스입니다. 5인 팀으로 개발했습니다.

**맡은 역할: 백엔드 · AI 학습**

- 작물 병해 이미지 진단 모델 학습 (고추·오이·호박·토마토의 정상/질병 8개 클래스)
- 학습한 모델을 Flask 예측 서버로 서비스화하고 웹과 연동
- NestJS·PostgreSQL 기반 JWT 회원가입·로그인, 사용자 프로필, 농사일지·내 작물 CRUD, 사진 업로드 구현
- Gemini API 증상 진단과 병해충 정보(NCPMS) API 연동, 프론트엔드 로그인·AI 채팅 연결

`Python` `TensorFlow/Keras` `Flask` `NestJS` `TypeScript` `PostgreSQL` `React`

저장소: [Frontend · AI](https://github.com/2uGod/Dandelion) · [Backend](https://github.com/MiMiMinGyu/SW_BE)

---

### 🧪 Other Projects

| 프로젝트 | 소개 | 기술 |
| --- | --- | --- |
| [destination](https://github.com/jinseojang0903/destination) | 지도에 다트를 던져 다음 여행지를 정하는 웹앱 | Next.js, TypeScript, Mapbox GL, Firebase |
| [barrier-free-map](https://github.com/jinseojang0903/barrier-free-map) | 사진 제보로 만드는 참여형 배리어프리 지도 프로토타입 | React, Vite, Kakao Maps SDK |
| [uglyfood-project](https://github.com/jinseojang0903/uglyfood-project) | 못난이 농산물을 등록하고 사고파는 웹 서비스 | Node.js, Express, EJS, lowdb |

---

### 🎖 Awards

| 수상 | 수여기관 | 시기 | 내용 |
| --- | --- | --- | --- |
| 양주시 미래인재 AI 공모전 **최우수상** | 양주시 | 2026년 10월 | 광역버스 만차 예보 AI "만차예보" (백엔드·데이터 수집·프론트엔드) |
| IC-PBL 경진대회 | 명지대학교 | 2025년 2학기 | 스스로 학습하는 제설 AI 웹 (팀장) |
| 창의적 SW프로그램 경진대회 | 명지대학교 | 2025년 2학기 | 농업 커뮤니티 웹 Farmunity |
| 장애인 인식제고 프로젝트 공모전 | 명지대학교 | 2022년 2학기 | 장애 체험 프로그램 "역지사지" 기획 |
| 역사 UCC 공모전 | 명지대학교 | 2022년 2학기 | 독도의용수비대 주제 UCC 제작 |

성적 우수 모범장학금 수혜 (3학년 2학기, 4학년 1학기)

---

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jinseojang4@gmail.com)
[![Blog](https://img.shields.io/badge/Blog-000000?style=flat-square&logo=naver&logoColor=white)](https://blog.naver.com/jinseojang)
