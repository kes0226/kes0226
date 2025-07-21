## Welcome! 👋

<!--
**kes0226/kes0226** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
영남대학교 컴퓨터공학과 김은서입니다.

## Tools & Technologies
- **Programming Languages** : java, python
- **frameworks** : spring, pytorch
- **Tools** : Git, Docker

## How to reach me
- **Github** : [@kes0226](https://github.com/kes0226)
- **email** : es7837@naver.com

## 주요 프로젝트

### 1. 펀딩 플랫폼 for 학생 크리에이터
학생들이 자신의 창작물을 등록하고 펀딩을 받을 수 있는 웹 서비스입니다.
#### 🧩 핵심 기능
- 사용자 펀딩 상품 등록 및 관리 (CRUD)
- 필터 기반 펀딩 검색 기능
- 회원가입 / 로그인 기능
- 결제 기능 (간편 결제 연동)
- 마크다운 에디터(Toast UI) 활용한 상세 상품 소개
#### 💻 사용 기술
- AWS, Docker, Spring Boot, MySQL, React
#### ⚙️ 역할 : Backend (Spring Boot, MySQL)
- 펀딩 등록/조회/수정/삭제 기능 구현 (CRUD)
- 이미지, 파일 업로드 기능 구현 (이미지 URL 저장 방식 사용)
- Toast UI 에디터 연동

---

### 2. 감정 기반 영화 추천 사이트
사용자의 감정 상태를 분석하고, 이에 적절한 감정 태그 기반 영화 추천을 제공하는 웹 사이트입니다.
#### 🧩 핵심 기능
- 감정 설문 조사를 통한 사용자 감정 분석
- 영화별 감정 태그(GPT 기반)와 사용자 감정 매칭을 통한 맞춤형 영화 추천
- 응원 메시지 생성 (GPT API 사용)
- 결과 공유 기능 (카카오 링크 API 활용)
#### 💻 사용 기술
- AWS, Spring Boot, MySQL, React, GPT API
#### ⚙️ 역할 : Backend (Spring Boot, GPT API, MySQL)
- GPT API + TMDB API를 활용한 영화 감정 태그 자동화 로직 구현
  - TMDB 영화 데이터를 GPT로 감정 분석 + 해석 후 저장
- GPT를 활용해 사용자 감정에 맞는 응원 메시지 자동 생성
  - 프롬프트 최적화해 적절한 응원 메시지 생성

---

### 3. 개발자 팀 프로젝트 매칭 플랫폼
개발자들이 사이드 프로젝트 팀원을 모집하고 참여할 수 있는 웹 플랫폼입니다.
#### 🧩 핵심 기능
- 팀 프로젝트 모집글 생성 / 수정 / 삭제
- 프로젝트 지원 및 팀 구성 기능
- 추천 알고리즘을 통한 정렬 기능
- 필터링 기반 검색 기능
- 팀 관리 페이지 및 실시간 마인드맵 기능
- 실시간 알림 기능
#### 💻 사용 기술
- AWS, Docker, Spring Boot, MySQL, React
#### ⚙️ 역할 : DevOps&Backend (Docker, Spring Boot, MySQL)
- 프로젝트 전체 Docker 컨테이너화 및 AWS 배포
- 필터링 검색 기능 구현
- 팀 관리 기능 백엔드 구현 (팀 구성 및 정보 조회 등)
