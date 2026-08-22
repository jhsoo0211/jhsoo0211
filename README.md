## 👋 안녕하세요, 정현수입니다

금융 데이터의 **정확성**, 외부 연동의 **실패 경계**, 다시 확인할 수 있는 **검증 근거**를 중요하게 생각하는 백엔드 개발자입니다.

`Financial Backend` · `Java / Spring` · `Data-intensive Systems`  
건국대학교 컴퓨터공학부 4학년 · Seoul

[Portfolio](https://app.notion.com/p/3c38a4915b1681819072c9ac96dbc358) · [Email](mailto:jhsoo0211@naver.com)

### 🔎 Backend Focus

- **Correctness first** — 금액·시세·추천 계산과 AI 생성 문장을 분리하고, 검증 가능한 값만 응답에 사용합니다.
- **Fail closed** — 인증·외부 API·토큰·데이터 신선도 조건이 불완전하면 성공처럼 보이지 않도록 경계를 둡니다.
- **Evidence over claims** — 테스트, CI, PR, ADR, 실행 기록으로 구현 범위와 미검증 범위를 함께 남깁니다.

### 🧩 Featured Backend & Data Projects

백엔드 채용 신호가 강한 순서로 정리했습니다.

| Priority | Project | Backend/Data work | Evidence & boundary |
|---|---|---|---|
| **1** | **IfSave** 🔒 | 25개 자산의 시점별 기회비용 계산, 소비 입력 3경로, 안전 경계를 둔 AI 해석, 캐시·DB 마이그레이션 | 2인 팀에서 Backend·Data·AI·Infra·기획 담당 · AI 페르소나 6종 · 고정 데모 거래 127건 · Java 21 / Spring Boot 3 / PostgreSQL 16 |
| **2** | **Distributed Shared Editor** 🔒 | Spring Boot 노드 간 Ricart–Agrawala 상호배제, Lamport clock, REQUEST/REPLY/HELD/RELEASE, late-comer SYNC | 2인 팀 · Java 17 / Spring Boot / JPA / H2 / STOMP / SockJS · [Demo](https://www.youtube.com/watch?v=CVRLt1_CdIM) · 운영 환경·최신 테스트 정합성은 미재검증 |
| **3** | **[ReGrip](https://github.com/jhsoo0211/ReGrip)** | 서버 권위 세션·XP 원장, JWT/회전 refresh token, localStorage↔REST 전환, 멱등 아웃박스 | Canvas 게임 4종 · FastAPI API · pytest/httpx 기반 API 테스트 · ESP32는 연동 트랙이며 실기기·임상 성능은 미검증 |
| **4** | **[MarkLens](https://github.com/davinida/marklens)** | KIPRIS 수집·정제, PDF 이미지 추출, OpenCLIP 임베딩, FAISS Top-K, FastAPI 검색 API | 연구 샘플 1,000건 · 512D 임베딩 · Python 337 passed/5 skipped · Vitest 34/34 · E2E 9/9 · 법률 판단 서비스가 아님 |
| **5** | **DearBloom** 🔒 | 독성·예산·제외 조건 hard filter → 가중치 → 다양성 선택 → LLM fallback의 결정적 추천 파이프라인 | 꽃 59종 · 이야기 438편 · 탄생화 366일 · 테스트 761개 · 편지는 localStorage, Supabase·실 LLM·공개 배포는 미검증 |

🔒 비공개 저장소의 구현 근거와 화면은 [Portfolio](https://app.notion.com/p/3c38a4915b1681819072c9ac96dbc358)에 정리했습니다.  
[IfSave Case Study](https://app.notion.com/p/3b78a4915b16814c8ed3fcb9389ae8a4) · [DearBloom Case Study](https://app.notion.com/p/3be8a4915b16810aa30dc9922e519754)

### 🌐 Engineering Evidence

#### [KUIT Android Portfolio](https://github.com/jhsoo0211/KUIT_Refactory)

`2025.03–2025.08` · 11인 팀 · Android 주요 기여자 1/4

- 루틴·피드·검색·프로필·팔로우·알림/FCM을 중심으로 [16개 PR 병합](https://github.com/jhsoo0211/KUIT_Refactory/blob/main/docs/CONTRIBUTIONS.md)
- Debug/Release 각각 JVM 테스트 32개 통과, lint error 0, main CI
- TLS, 토큰·세션, 민감 로그, 실패 시 기존 데이터 보존 경계 보강

모바일 프로젝트이지만 **협업 이력, 인증·네트워크 경계, 테스트와 CI**를 공개 저장소에서 직접 검증할 수 있어 별도 증거로 배치했습니다.

### 🛠 Stack by Backend Relevance

- **Backend** — Java, Spring Boot, JPA, REST API, Python, FastAPI
- **Data** — PostgreSQL, SQLite, Flyway, FAISS, OpenCLIP
- **Reliability** — JUnit, Pytest, Vitest, Playwright, GitHub Actions, lint/typecheck
- **Client integration** — TypeScript, Next.js, React, Kotlin, Jetpack Compose

### 📚 Additional Work

- **[cv-panorama-stitching](https://github.com/jhsoo0211/cv-panorama-stitching)** — 1,000만 픽셀 메모리 예산을 둔 OpenCV 파노라마 스티칭 파이프라인과 회귀 테스트
- **[MyCo-Kit](https://github.com/jhsoo0211/Myco-Kit)** — 버섯 폐배지 기반 자원순환 STEAM 키트의 React/TypeScript 랜딩 페이지 · [Live](https://ornate-beignet-ae6be6.netlify.app/)
- **[Business Planner Skills](https://github.com/jhsoo0211/bussiness-planner-skills)** — PSST 프레임워크 기반 사업계획서 작성 도구

### 🎓 Education & Activities

- `2020.03–현재` 건국대학교 컴퓨터공학부
- `2026` IfSave 드림학기제 선정 · ReGrip 경기청년 갭이어 선정 · MyCo-Kit U300 성장트랙 참여

> 공개 수치는 저장소 테스트·실행 기록 또는 프로젝트 문서로 확인 가능한 범위만 적었습니다. 검증되지 않은 운영 배포·사용자·임상·매출 성과는 구분합니다.

