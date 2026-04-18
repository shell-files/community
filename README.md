# 🌿 ESG 탄소배출량 관리 시스템 (ESG Carbon Emission Management System)
> **Team WITH (We are IT Hero)** > "데이터로 세상을 구하는 IT 영웅들의 지속 가능한 솔루션"

---

## 🚀 Project Overview
기업의 탄소 배출 데이터를 효율적으로 수집, 계산하고 관리하기 위한 ESG 통합 관리 플랫폼입니다. 복잡한 배출량 산정 프로세스를 자동화하여 데이터 기반의 투명한 ESG 경영을 지원합니다.

## 🛠 Tech Stack
- **Frontend:** React
- **Backend:** Python (FastAPI), Apache Spark (데이터 처리)
- **Database:** SQL, Docker (Containerization)
- **Tooling:** GitHub Actions (CI/CD)

---

## 📜 Collaboration Rules (Git Flow)

우리는 효율적인 협업과 코드 품질 유지를 위해 아래의 Git 전략을 준수합니다.

### 📍 Branch Strategy
- **Main**: 최종 배포 브랜치 (안정성이 검증된 코드만 병합)
- **Release**: 주 단위 배포 및 버전 관리 브랜치 (`v0.1.0` 형식)
- **Develop**: 개발 통합 브랜치 (모든 기능 합류점)
- **Feature**: 개별 기능 구현 브랜치 (**작업 후 삭제 원칙**)

### 🏷 Naming Convention
- **Format**: `종류/기능명_이니셜`
- **Rules**: 소문자 사용, 단어 구분은 언더바(`_`)
- **Example**: 
  - `feat/login_yuj` (로그인 기능 개발)
  - `fix/db-connection_hsh` (DB 연결 오류 수정)

### 🔄 Workflow
1. `develop` 브랜치에서 본인의 `feature` 브랜치를 생성합니다.
2. 기능 구현 후 `develop` 브랜치로 **PR(Pull Request)**을 보냅니다.
3. 코드 리뷰 및 테스트 완료 후 머지하며, 사용이 끝난 브랜치는 삭제합니다.

### 🛠 Development Standards
- **Error Handling:** 전역 예외 처리기 사용 및 표준 응답 포맷 준수
- **Logging:** 로그 레벨(INFO, WARN, ERROR) 구분 및 타임스탬프 포함
- **Database:** DB 직접 접근 지양, DAO/Repository 패턴 및 정해진 프로시저 규칙 사용
- **Security:** 개인정보 및 탄소 배출 데이터 암호화 처리 필수

### 🤝 Workflow & Organization
- **Team Structure:** 각 기능팀(UI/DB/Back) 당 1명씩 배정하여 Cross-functional하게 운영
- **Issue Management:** 통일된 Issue Template을 사용하여 개발 태스크 기록
- **Documentation:** WBS 기반 일정 관리 및 회의록(Decision Log) 상시 업데이트

---

## 🗓 Roadmap & Schedule
- **2026-04-20**: 작업 분류(R&R) 및 상세 설계 확정
- **2026-04-21**: CI/CD 파이프라인 구축 및 암호화 모듈 개발
- **2026-06-23**: 최종 시스템 구축 완료 및 시연

---

## 👥 Contributors
- **Project Manager**: Cho Youn Ju (@frankie516c)
- **Team Members**: WITH Team Developers

