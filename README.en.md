[한국어](./README.md) · **English**

# 👋 JEONGHYEONSU | Backend & Data Engineer

Computer Science & Engineering at Konkuk University · Seoul, Korea

I build backend services and data pipelines where calculations, external data, and AI-generated explanations need clear boundaries.

Recent work includes:
- a financial backend that fixes a hypothetical position at purchase time and calculates its later opportunity cost,
- a KIPRIS → OpenCLIP → FAISS pipeline for trademark-image retrieval,
- and a distributed shared editor using Ricart–Agrawala mutual exclusion and Lamport clocks.

`Java / Spring Boot` · `PostgreSQL` · `Python / FastAPI` · `Data-intensive Systems`

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

[Portfolio](https://app.notion.com/p/3c38a4915b1681819072c9ac96dbc358)

## Selected Projects

| Project | What I worked on | Stack / current scope |
|---|---|---|
| **IfSave** 🔒 · [Case Study](https://app.notion.com/p/3b78a4915b16814c8ed3fcb9389ae8a4) | Built the backend/data/AI flow for comparing a purchase with 25 predefined assets. A purchase fixes hypothetical quantities first; later prices are used for opportunity-cost calculations. Manual/CSV/OCR inputs and six AI personas are connected while numeric calculation stays outside the LLM path. | Java 21 · Spring Boot 3 · PostgreSQL 16 · private repository |
| **[Distributed Shared Editor](https://github.com/jhsoo0211/distributed-systems-team7)** | Implemented Ricart–Agrawala distributed mutual exclusion, Lamport-clock ordering, REQUEST/REPLY/HELD/RELEASE handling, WebSocket synchronization, and late-comer session sync. | Java 17 · Spring Boot · JPA · H2 · STOMP/SockJS · [Demo](https://www.youtube.com/watch?v=CVRLt1_CdIM) |
| **[MarkLens](https://github.com/davinida/marklens/tree/develop)** | Worked on the trademark-search data path: KIPRIS collection/cleanup, image extraction, OpenCLIP 512D embeddings, FAISS Top-K retrieval, and FastAPI serving. The current develop track uses a limited 1,000-trademark research sample and reports visual similarity only. | Python 3.11 · FastAPI · OpenCLIP · FAISS · PostgreSQL |
| **[ReGrip](https://github.com/jhsoo0211/ReGrip)** | Connected four Canvas rehabilitation games to a replaceable `DataService` layer (`localStorage` ↔ REST), session/XP records, and offline-first persistence. | FastAPI · SQLAlchemy · Vanilla JS · Canvas 2D · software/simulation validation |

## Collaboration Evidence

### [KUIT Android Portfolio](https://github.com/jhsoo0211/KUIT_Refactory)

`2025.03–2025.08` · Android team project

- 16 pull requests merged into the original team repository under my GitHub account.
- Main areas: My Routine, Routine Feed, search, profile/follow flows, navigation, API integration, and FCM notifications.
- In the 2026 portfolio copy, I separately improved network boundaries, failure-state handling, tests, CI, and documentation.

[Contribution log](https://github.com/jhsoo0211/KUIT_Refactory/blob/main/docs/CONTRIBUTIONS.md)

## Stack

- **Backend** — Java, Spring Boot, JPA, REST API, Python, FastAPI
- **Data** — PostgreSQL, SQLite, Flyway, FAISS, OpenCLIP
- **Reliability** — JUnit, pytest, Vitest, Playwright, GitHub Actions, lint/typecheck
- **Client integration** — TypeScript, Next.js, React, Kotlin, Jetpack Compose

## Other Work

- **[cv-panorama-stitching](https://github.com/jhsoo0211/cv-panorama-stitching)** — OpenCV panorama-stitching pipeline built around a 10-million-pixel memory budget and regression tests.
- **[MyCo-Kit](https://github.com/jhsoo0211/Myco-Kit)** — React/TypeScript landing page for a circular-economy STEAM mycelium kit. [Live](https://ornate-beignet-ae6be6.netlify.app/)
- **[Business Planner Skills](https://github.com/jhsoo0211/bussiness-planner-skills)** — tooling for drafting business plans around the Korean PSST framework.

## Education & Activities

- `2020.03–Present` B.S. in Computer Science & Engineering, Konkuk University
- `2026` IfSave Dream Semester · ReGrip Gyeonggi Youth Gap Year · MyCo-Kit U300 Growth Track

> Project status and validation scope follow the corresponding repositories and project documents. Unverified production, clinical, or legal-performance claims are kept separate from implemented functionality.
