# 🎫 쏠로구독 (SoloGudok)

**소비내역을 기반으로 구독 서비스를 추천하고 관리할 수 있는 플랫폼**  
개인의 소비 패턴을 분석하여 맞춤형 구독 조합 및 추천 서비스를 제공하는 스마트한 구독 관리 시스템입니다.

---

## 📌 프로젝트 개요

- **프로젝트명**: 쏠로구독 (SoloGudok) – 구독 서비스 관리 플랫폼
- **진행 기간**: 2025년 2월 10일 ~ 2025년 3월 25일
- **개발 인원**: 총 5명 (기획, 프론트, 백엔드 전원 참여)
- **레포지토리 구성**:
  - 🔧 [Backend Repository](https://github.com/SoloGudok/BACKEND)
  - 🖥 [Frontend Repository](https://github.com/SoloGudok/FRONTEND)

---

## 🛠 기술 스택

### Backend
- Java 17
- Spring Boot
- JPA, QueryDSL
- MySQL (AWS RDS)
- Swagger / Postman (API 문서화)

### Frontend
- React.js
- Chart.js / ApexChart

### Infra & DevOps
- AWS RDS, AWS S3 (Presigned URL 이미지 업로드)
- Podman (프론트, 백, DB 컨테이너화)
- GitHub, Figma

---

## 💡 프로젝트 소개

쏠로구독은 **개인의 카드 소비 데이터를 분석**하여  
현재 구독 중인 서비스 현황을 시각적으로 보여주고,  
맞춤형 구독 서비스와 카드까지 추천해주는 구독 관리 플랫폼입니다.

구독 조합 상품, 구독 해지 기능, 연령대 비교 차트 등  
실제 사용자의 패턴을 반영한 구독 관리 기능을 구현했습니다.

---

## 🎯 프로젝트 목표

- 카드 소비 데이터를 분석하여 구독 소비 성향 시각화
- 개인별 맞춤 구독 추천 및 할인 조합 상품 제공
- 구독 서비스의 통합 관리(구독, 해지, 조합 등)
- 사용자 중심의 UI/UX 설계 및 데이터 기반 차트 분석 기능 구현

---

## 🧩 주요 기능

![조합 상품 기능](https://github.com/user-attachments/assets/f52b50f5-22dd-4fcc-b8a8-1651927dcc13)


### ✅ 구독 조합 기능
- 사용자가 선택한 구독 서비스 3개로 조합 상품 생성
- 조합 상품 결제 시 자동 할인 적용

---


<img src="https://github.com/user-attachments/assets/082ad324-3358-4145-ac2a-883bcda7b72f" alt="추천 기능" width="500"/>


### ✅ 소비 데이터 기반 추천
- 카드 소비내역 분석 후 구독 서비스, 카드 추천  
- 카테고리별 지출 금액, 구매 빈도를 기반으로 개인화된 제안

---


![대시보드](https://github.com/user-attachments/assets/55b08f84-4614-4fcd-84a1-c91d02b7d7b9)


### ✅ 사용자 맞춤형 대시보드
- 월별/카테고리별 소비 내역 시각화 (차트)
- 같은 연령대 소비자와의 비교 차트 제공

---

### ✅ 구독 서비스 관리

- 현재 구독 중인 서비스 목록 및 해지 기능
- 개별 구독/조합 구독의 상태 관리


---

## 🔧 ERD 설계

![ERD 다이어그램](https://github.com/user-attachments/assets/20e3d66c-6413-437e-b0f1-5ff0f522d7cf)

ERD는 사용자, 구독 서비스, 조합 상품, 소비 내역, 카드, 카테고리 등을 중심으로 정규화되어 있으며,  
실제 시나리오 기반의 도메인 설계를 통해 유연한 확장성과 관리가 가능하도록 설계되었습니다.

---


> 쏠로구독은 구독 서비스에 대한 **합리적 소비와 자동 추천**을 목표로 한 프로젝트로,  
> 실제 소비 데이터를 기반으로 개인 맞춤형 혜택과 분석을 제공하는 기능을 중심으로 설계되었습니다.
