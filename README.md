# EcoStory - 환경 정보 조회 서비스

EcoStory는 공공데이터 API를 활용하여 **지역 환경 정보를 조회하고 공유할 수 있는 서비스**입니다.

사용자는 지역별 환경 지수를 확인할 수 있으며  
게시판을 통해 환경 관련 정보를 공유할 수 있습니다.

---

# 📌 Project Overview

EcoStory는 공공데이터 포털에서 제공하는 환경 데이터를 활용하여  
지역별 환경 정보를 조회할 수 있도록 만든 서비스입니다.

환경 정보 데이터는 주기적으로 업데이트되며  
사용자는 게시판을 통해 환경 관련 정보를 공유할 수 있습니다.

---

# 🚀 주요 기능

### 환경 정보 조회
- 공공데이터 API를 통해 지역별 환경 지수 조회
- 환경 데이터를 사용자에게 제공

### 데이터 업데이트
- 공공데이터 API를 통해 환경 정보 주기적 업데이트
- 최신 환경 정보 유지

### 게시판 기능
- 게시글 작성
- 게시글 조회
- 게시글 수정
- 게시글 삭제

### 지역 기반 정보 조회
- 지역별 환경 정보 확인 가능

---

# 🧩 System Architecture

```
Client
   │
   ▼
Node.js Backend
   │
   ├── Environment Data API
   │
   ▼
Public Data API
   │
   ▼
Database
```

---

# 🛠 Tech Stack

### Backend
- Node.js
- Express

### Database
- MySQL

### External API
- 공공데이터 포털 Open API

### Infrastructure
- AWS EC2

### Communication
- REST API

---

# 👨‍💻 My Role

- 공공데이터 API 연동
- 환경 데이터 조회 기능 구현
- 게시판 CRUD 기능 구현
- 환경 데이터 업데이트 로직 구현

---

# 📂 기능 흐름

### 환경 정보 조회

```
사용자 요청
   │
   ▼
환경 데이터 조회 API
   │
   ▼
공공데이터 API 요청
   │
   ▼
환경 데이터 반환
```

---

### 게시판 기능

```
사용자
   │
   ▼
게시글 작성
   │
   ▼
Database 저장
   │
   ▼
게시글 조회
```

---

# 💡 What I Learned

- 외부 공공데이터 API 연동 경험
- REST API 기반 서버 개발
- 게시판 CRUD 기능 구현
- 주기적 데이터 업데이트 구조 설계
