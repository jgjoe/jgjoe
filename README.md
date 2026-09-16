# 조지관 (Jigwan Joe)

시스템을 만들고, 품질을 수치로 확인한 뒤 배포 여부를 판단합니다.
IT시스템·SI·전산과 소프트웨어 품질을 중심으로, 백엔드와 AI 솔루션 직무까지 지원하고 있습니다.

[![Portfolio](https://img.shields.io/badge/포트폴리오-jgjoe.github.io-success)](https://jgjoe.github.io/my-portfolio/)
[![Email](https://img.shields.io/badge/email-jigwan.joe%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:jigwan.joe@gmail.com)
[![Stack](https://img.shields.io/badge/Java%20%C2%B7%20Kotlin%20%C2%B7%20Python-Spring%20Boot%20%C2%B7%20FastAPI-informational)](#기술)

---

### 검증한 결과

무엇을 만들었는지는 아래 저장소 설명에, 측정 조건과 함께 나빠진 지표는 각 README에 적어 두었습니다.

| 프로젝트 | 검증된 결과 |
|---|---|
| **[혜택나침반](https://github.com/jgjoe/benefit-compass)** | 자체 라벨링 60문항 평가셋 기준 recall@1 0.40 → 0.52 · 정책 2,631건 · [평가셋·측정 스크립트 공개](https://github.com/jgjoe/benefit-compass/tree/main/eval) |
| **[오늘도 신선](https://github.com/jgjoe/Fridge-D-Day)** | 한국 라벨 55장 · D-30 시나리오 기준 OCR 일치율 67.27% → 72.73% · 잔여 오답으로 배포를 보류한 뒤 사용자 확인 흐름을 넣어 재출시 ([QA 기록](https://github.com/jgjoe/Fridge-D-Day/blob/main/QA_RELEASE_RECORD.md)) |
| **[gildongE](https://github.com/jgjoe/gildongE)** | 5개 도메인 REST API와 MongoDB 문서 모델 · 캡스톤 은상, 학회 논문 공저 |
| **[Build Your Health](https://github.com/jgjoe/Build-Your-Health)** | 프레임워크 없이 JSP/Servlet만으로 업무 도메인 8개·JSP 54개 · 필터로 요청 경로·처리 시간 로깅 |
| **[Movie Diary](https://github.com/jgjoe/movie_diary)** | Gemini 호출 async 전환 · Cloud Run scale-to-zero로 상시 서버 비용 제거 |

### 오픈소스

- [pydantic/logfire #2260](https://github.com/pydantic/logfire/pull/2260) — CLI 기본 URL을 `LOGFIRE_BASE_URL` 환경변수에서 읽도록 하는 PR 제출 · maintainer 검토 대기 중
- [huggingface/sentence-transformers #3923](https://github.com/huggingface/sentence-transformers/issues/3923) — scale-to-zero 콜드스타트를 구간별로 측정해 배포 가이드 문서화를 제안(이슈)

### 기술

**언어** Java · Kotlin · Python · JavaScript · SQL
**백엔드** Spring Boot · FastAPI · REST API · OpenAPI
**데이터** MySQL · PostgreSQL(pgvector) · MongoDB
**품질·운영** JUnit · GitHub Actions · Prometheus · Docker · Google Cloud Run
