# 👋 안녕하세요, 프론트엔드 엔지니어 박민선입니다.

단순히 화면을 구현하는 것을 넘어, **서버와 엣지, 네트워크 파이프라인 전반을 분석하여 사용자 화면에 닿기까지의 병목을 해결**하는 데 몰입합니다.  
브라우저 너머의 인프라 흐름까지 이해하며 서비스의 체감 속도와 완성도를 극대화합니다.

---

## 🚀 Key Highlights & Numbers

- **LCP 대기 시간 89% 단축**: Cloudflare Pages Functions 기반 엣지 HTML 데이터 사전 주입 및 스트리밍 파싱 (530 ~ 710ms → 70~80ms)
- **SPA 체감 전환 지연 97.9% 단축**: 사용자 인터랙션 기반 백그라운드 프리페칭과 LRU 인메모리 캐싱으로 Soft LCP 최적화 (2.22s → 0.046s)
- **서버리스 세션 동기화 및 TTFB 72.7% 단축**: Vercel 다중 인스턴스 레이스 컨디션을 Upstash Redis Grace Period 캐싱으로 해결 (86.42ms → 23.57ms)
- **Next.js SSR 전환을 통한 초기 렌더링 개선**: 경량 HTML 서빙 및 LCP 30% 단축, 첫 진입 스켈레톤 UI 제거

---

## 🛠 Tech Stack

### Frontend
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React%20Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
</p>

### Infra, Edge & Database
<p>
  <img src="https://img.shields.io/badge/Cloudflare%20Pages%20/%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Upstash%20Redis-00E599?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
</p>

### Backend & Protocol
<p>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white"/>
</p>

---

## 📌 Featured Projects

### 1. Deeps (2026.06 - 진행 중)
> **스터디원 간 문제 생성 및 공유를 통해 주도적 학습 환경을 제공하는 스터디 플랫폼**
- **역할**: 프론트엔드 (홈/상세 뷰, 공통 UI), 도메인 API 개발, 서버 배포
- **핵심 작업**:
  - Vercel 분산 서버리스 환경에서 발생하는 토큰 레이스 컨디션을 Upstash Redis 및 Grace Period(30초) 캐싱 패턴으로 해결하여 TTFB 72.7% 단축
  - Next.js Server Component 기반 SSR 전환으로 직렬 네트워크 홉 제거 및 LCP 약 30% 단축
  - Compound Component 패턴 기반의 Flexible Modal 시스템 및 재사용 공통 UI 추상화

---

### 2. SEON Blog (2026.04 - 진행 중)
> **Cloudflare Pages & D1 기반의 엣지 렌더링 최적화 기술 블로그**
- **역할**: 1인 기획 및 풀스택 개발
- **핵심 작업**:
  - Cloudflare Pages Functions 및 HTMLRewriter 기반 엣지 HTML 데이터 사전 주입으로 CSR 스켈레톤 깜빡임 제거 및 LCP 대기 시간 89% 단축
  - React Router 번들 분할 및 상단 요약 데이터 사전 바인딩으로 SPA Soft LCP 97.9% 단축 (2.22s → 0.046s)
  - 마우스 호버/터치 기반 프리페칭과 LRU 인메모리 캐시 파이프라인으로 체감 지연 0ms 구현 및 D1 쿼리 호출 절감

---


## 🏆 Awards & Activities

- **2025 SW중심대학 디지털 경진대회 SW부문 우수상** (SignOrder)
- **2025 국민대학교 캡스톤 디자인 어워드 최우수상** (SignOrder)
- **국민대학교 소프트웨어전공** (2021.03 - 2027.02 졸업예정)

---

## 📬 Contact & Links

- **Email**: decollzoq@gmail.com
- **Blog**: [SEON Blog](https://seon-log.pages.dev) <!-- 실제 블로그 URL로 확인해 주세요 -->
