# 최현진 | Software Engineer

문제를 구조화하고, 측정과 테스트로 결과를 검증하는 신입 소프트웨어 엔지니어입니다.  
건국대학교 글로컬캠퍼스에서 컴퓨터공학과 빅데이터융합전공을 이수하고 있으며, KRAFTON JUNGLE에서 백엔드·프론트엔드·운영체제·AI 응용 프로젝트를 수행했습니다.

## Featured Projects

### [Dazzajo — AI PC 견적·AS 통합 서비스](https://github.com/jungle-final-project/prototype)

- 5인 팀 프로젝트
- React·TypeScript, Spring Boot(Java 21), PostgreSQL·pgvector, Redis, RabbitMQ, Docker
- AI Agent·RAG 기반 견적 추천과 PC 진단 흐름, 성능 검증 및 상태형 QA 구현
- 상대 성능 변경 요청을 결정적 fast path로 분리해 해당 요청군을 로컬 실측 15~66ms에 처리

### [Project Alpha — Hybrid RAG·MCP·AI Agent 지식 게시판](https://github.com/Jungle-12-303/week15-16_team03_ai_board_lab/tree/HYUNJIN)

- 개인 프로젝트
- React, Spring Boot, MySQL, Qdrant
- Vector Search와 BM25를 RRF로 결합한 Hybrid RAG, MCP 기반 GitHub·날씨 팩트체크, 열람 이력 기반 추천 Agent 구현
- 게시글 벡터 1,307개·청크 벡터 5,419개를 대상으로 한 소규모 평가(6개 질의)에서 Precision@5 0.8667, MRR@5 1.0000 기록

### [KAIST Pintos — Virtual Memory](https://github.com/Jungle-12-303/week11-team-03-pintos-vm)

- Supplemental Page Table, lazy loading, `mmap`/`munmap`, dirty page write-back 구현
- FIFO 교체 정책을 second-chance 방식으로 개선하고 fork 과정의 페이지·파일 생명주기 처리

### [Vanilla JavaScript UI Runtime — VDOM to Hooks](https://github.com/Jungle-12-303/week5-team3-react2)

- VDOM diff/patch와 keyed reorder에서 출발해 `useState`, `useEffect`, `useMemo`를 지원하는 런타임으로 확장
- microtask batching과 effect cleanup을 구현하고 자동화 테스트로 동작 검증
- 이전 단계: [VDOM Visualizer](https://github.com/choihyunjin1/week4_project)

## Tech

- **Backend:** Java, Spring Boot, Python, REST API
- **Frontend:** React, TypeScript, JavaScript, Vite
- **AI & Data:** RAG, AI Agent, MCP, Qdrant, pgvector, PostgreSQL
- **Systems:** C, Pintos, Virtual Memory
- **Infra:** Docker, Redis, RabbitMQ

## AI-assisted Development

Claude와 Codex를 요구사항 분해·탐색·구현 보조에 활용합니다. 아키텍처 선택, 검증 기준 수립, 테스트와 결과 확인은 직접 책임지는 방식으로 작업합니다.
