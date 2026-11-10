# (주)도스코 열처리 관제 대시보드 및 하네스 시스템

(주)도스코 특수마대강 연속열처리 전력·온도 통합 관제 및 엑셀 1:1 생산일지 전산화 시스템 저장소입니다.

## 주요 포함 문서 및 엔지니어링 명세

- **[DOSKO_HARNESS_ENGINEERING.md](DOSKO_HARNESS_ENGINEERING.md)**: 열처리 전력·온도 통합 관제 및 생산일지 시스템 하네스 엔지니어링 정본 (설비 6개 라인 조업 사양, 5단계 생산 프로세스, 18개 타겟 동기화 체계)
- **[GEMINI.md](GEMINI.md)**: AI 하네스 운영 규칙, 세션 회고 트리거, 인코딩 및 배포 가드레일
- **[LESSONS_LEARNED.md](LESSONS_LEARNED.md)**: 하네스 엔지니어링 실수 복기 및 재발 방지 누적 회고록
- **[ONBOARDING.md](ONBOARDING.md)**: 물류 및 현장 작업자 온보딩 가이드

## 서비스 실행 및 동기화

- **사내 관제 서버 포트**: 8089 (통합 RBAC 인증, PLC 수신 및 대시보드 서빙)
- **실행 명령**:
  `powershell
  python dosko_sync_server.py
  `
