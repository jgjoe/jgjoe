# 조지관 (Jigwan Joe)

**만든 것이 실제로 동작하는지 재고, 그 결과로 배포 여부를 판단합니다.**
IT시스템·SI / QA·TestOps / 백엔드 직무를 중심으로 지원하고 있습니다.

[![Portfolio](https://img.shields.io/badge/포트폴리오-crushonyou2.github.io-success)](https://crushonyou2.github.io/my-portfolio/)
[![Email](https://img.shields.io/badge/email-jigwan.joe%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:jigwan.joe@gmail.com)
[![Stack](https://img.shields.io/badge/Java%20%C2%B7%20Kotlin%20%C2%B7%20Python-Spring%20Boot%20%C2%B7%20FastAPI-informational)](#기술)

---

### 대표 프로젝트

| 프로젝트 | 무엇을 만들었나 | 검증된 결과 |
|---|---|---|
| **[혜택나침반](https://github.com/crushonyou2/benefit-compass)** | 청년정책 RAG 검색 서비스. 수집·정제부터 임베딩·벡터검색·리랭킹·생성, 배포·관측까지 단독 | **정답을 라벨링한 60문항 평가셋을 직접 만들어** 검색 품질을 측정 — recall@1 0.40 → 0.52, MRR 0.535 → 0.614(recall@5·@10은 각 1문항 감소, 표본이 작아 유의성 판단 보류하고 함께 기록) · 정책 2,631건 → 청크 3,083개, 임베딩 누락 0건 · 평가셋·측정 스크립트 전부 공개 |
| **[오늘도 신선](https://github.com/crushonyou2/Fridge-D-Day)** | 유통기한 관리 Android 앱. 기획·개발·스토어 배포·운영 단독 | 원스토어 배포 2건 · **독립 한국 라벨 55장 · D-30 시나리오 기준** 정확 일치율 67.27% → 72.73% · 단위 29건·계측 15건 · **잔여 오답을 근거로 배포를 보류한 뒤 원인을 제품 구조로 해결해 재출시** |
| **[gildongE](https://github.com/crushonyou2/gildongE)** | 7인 팀 AI 차량 어시스턴트의 백엔드 담당 | 차량·차종·소모품·주행패턴·사용자 **5개 도메인 REST API**와 MongoDB 문서 모델 · 캡스톤 경진대회 **은상**, 학회 논문 공저 |
| **[Build Your Health](https://github.com/crushonyou2/Build-Your-Health)** | 사내 웹 시스템 형태의 건강 관리 애플리케이션. 화면·서버·DB·관리자 기능 단독 | 프레임워크 없이 JSP/Servlet만으로 **업무 도메인 8개·JSP 54개** 구현 · DAO/DTO 분리 · 필터로 요청 경로와 처리 소요 시간 로깅 |
| **[Movie Diary](https://github.com/crushonyou2/movie_diary)** | 일기 감정 분석 기반 영화 추천 | 외부 API 두 곳을 다루려 FastAPI를 골라 Gemini 호출을 async로 전환(TMDB는 아직 동기) · Cloud Run scale-to-zero로 상시 서버 비용 제거 · 프론트는 GitHub Actions 자동 배포 |

### 일하는 방식

- **측정 환경을 먼저 만듭니다.** 표본과 조건을 고정해야 개선했다고 말할 수 있습니다 — 60문항 평가셋, 55장 회귀 기준선이 그렇게 나왔습니다.
- **수치에는 조건을 붙입니다.** 어떤 표본, 어떤 시나리오에서 잰 값인지 없이 쓰지 않습니다.
- **기준에 못 미치면 내보내지 않고, 그 원인을 해결해 다시 냅니다.** 자동 검증을 다 통과한 릴리스를 잔여 오답 때문에 보류한 뒤, 잘못된 값이 저장되는 경로 자체를 없애고 재출시한 적이 있습니다.

### 오픈소스

- [pydantic/logfire #2260](https://github.com/pydantic/logfire/pull/2260) — CLI 기본 URL을 `LOGFIRE_BASE_URL` 환경변수에서 읽도록 하는 PR **제출·리뷰 진행 중**

### 기술

**언어** Java · Kotlin · Python · JavaScript · SQL
**백엔드** Spring Boot · FastAPI · REST API · OpenAPI
**데이터** MySQL · PostgreSQL(pgvector) · MongoDB
**품질·운영** JUnit · GitHub Actions · Prometheus · Docker · Google Cloud Run

### 자격

정보처리기사 · SQLD · ADsP · CSTS Foundation Level · 한국사능력검정시험 1급 · TOEIC 765

---

📍 Korea · ✉️ jigwan.joe@gmail.com · 🔗 [포트폴리오](https://crushonyou2.github.io/my-portfolio/)
