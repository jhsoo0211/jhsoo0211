[English](./README.md) · [한국어](./README.ko.md)

# 👋 정현수 | Backend & Data Engineer

건국대학교 컴퓨터공학부 · Seoul

저는 **계산 결과, 외부 데이터, AI가 만든 설명 사이의 경계를 코드로 분리하는 백엔드**를 만들고 있습니다.

최근에는 다음과 같은 문제를 직접 구현했습니다.
- **IfSave**에서 소비 시점의 가상 매수 수량을 먼저 확정하고, 이후 시세로 기회비용을 계산하는 금융 백엔드
- **MarkLens**에서 KIPRIS 데이터를 수집·정제한 뒤 OpenCLIP 임베딩과 FAISS 검색 API로 연결하는 데이터 파이프라인
- **분산 공유 편집기**에서 Ricart–Agrawala 상호배제와 Lamport clock으로 동시 편집 순서를 맞추는 분산 로직

`Java / Spring Boot` · `PostgreSQL` · `Python / FastAPI` · `Data-intensive Systems`

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

[포트폴리오 · 한국어](https://app.notion.com/p/3c38a4915b1681819072c9ac96dbc358) · [Portfolio · English](https://app.notion.com/p/3d18a4915b16814886e2d840e3c6e322) · [Email](mailto:jhsoo0211@naver.com)

## Selected Projects

| Project | 직접 다룬 부분 | Stack / 현재 범위 |
|---|---|---|
| **IfSave** 🔒 · [Case Study](https://app.notion.com/p/3b78a4915b16814c8ed3fcb9389ae8a4) | 소비를 국내 30종·미국 30종의 총 60개 자산과 비교하는 Backend·Data·AI 흐름을 구현했습니다. 소비 저장 시 가상 매수 수량을 먼저 고정하고 이후 가격으로 기회비용을 계산합니다. 수동/CSV/OCR 입력과 AI 페르소나 6종을 연결하되, 금액·수치 계산은 LLM 밖에서 처리합니다. | Java 21 · Spring Boot 3 · PostgreSQL 16 · 비공개 저장소 |
| **[Distributed Shared Editor](https://github.com/jhsoo0211/distributed-systems-team7)** | Ricart–Agrawala 분산 상호배제, Lamport clock 순서화, REQUEST/REPLY/HELD/RELEASE 처리, WebSocket 동기화, late-comer 세션 동기화를 구현했습니다. | Java 17 · Spring Boot · JPA · H2 · STOMP/SockJS · [Demo](https://www.youtube.com/watch?v=CVRLt1_CdIM) |
| **[MarkLens](https://github.com/davinida/marklens/tree/develop)** | KIPRIS 수집·정제, 이미지 추출, OpenCLIP 512차원 임베딩, FAISS Top-K 검색, FastAPI 서빙 흐름을 다뤘습니다. 현재 develop 기준 1,000건 연구 표본을 사용하며 결과는 시각 유사도 한 축으로 한정합니다. | Python 3.11 · FastAPI · OpenCLIP · FAISS · PostgreSQL |
| **[ReGrip](https://github.com/jhsoo0211/ReGrip)** | Canvas 재활 게임 4종을 교체형 `DataService`(`localStorage` ↔ REST), 세션·XP 기록, 오프라인 우선 저장 흐름과 연결했습니다. | FastAPI · SQLAlchemy · Vanilla JS · Canvas 2D · 소프트웨어/시뮬레이션 검증 단계 |

## Collaboration Evidence

### [KUIT Android Portfolio](https://github.com/jhsoo0211/KUIT_Refactory)

`2025.03–2025.08` · Android 팀 프로젝트

- 원본 팀 저장소에 제 GitHub 계정으로 **16개 PR이 병합**됐습니다.
- My Routine, Routine Feed, 검색, 프로필·팔로우, Navigation, 서버 API 연결, FCM 알림을 주로 맡았습니다.
- 2026년 개인 포트폴리오 사본에서는 네트워크 경계, 실패 상태 보존, 테스트, CI, 문서를 별도로 보강했습니다.

[Contribution log](https://github.com/jhsoo0211/KUIT_Refactory/blob/main/docs/CONTRIBUTIONS.md)

## Stack

- **Backend** — Java, Spring Boot, JPA, REST API, Python, FastAPI
- **Data** — PostgreSQL, SQLite, Flyway, FAISS, OpenCLIP
- **Reliability** — JUnit, pytest, Vitest, Playwright, GitHub Actions, lint/typecheck
- **Client integration** — TypeScript, Next.js, React, Kotlin, Jetpack Compose

## Other Work

- **[cv-panorama-stitching](https://github.com/jhsoo0211/cv-panorama-stitching)** — 1,000만 픽셀 메모리 예산을 둔 OpenCV 파노라마 스티칭 파이프라인과 회귀 테스트
- **[MyCo-Kit](https://github.com/jhsoo0211/Myco-Kit)** — 균사체 기반 자원순환 STEAM 키트의 React/TypeScript 랜딩 페이지 · [Live](https://ornate-beignet-ae6be6.netlify.app/)
- **[Business Planner Skills](https://github.com/jhsoo0211/bussiness-planner-skills)** — 한국 창업지원사업의 PSST(Problem·Solution·Scale-up·Team) 사업계획서 스킬 15종 · Claude Code·Codex 설치 지원 · [English guide](https://github.com/jhsoo0211/bussiness-planner-skills/blob/main/README.en.md)

## Education & Activities

- `2020.03–현재` 건국대학교 컴퓨터공학부
- `2026` IfSave 드림학기제 · ReGrip 경기청년 갭이어 · MyCo-Kit U300 성장트랙

> 프로젝트 상태와 검증 범위는 각 저장소와 프로젝트 문서를 기준으로 적었습니다. 아직 검증하지 않은 운영·임상·법률 성능은 구현 완료 기능과 구분합니다.
