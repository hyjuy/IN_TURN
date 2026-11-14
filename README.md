# 개발 시작 안내

## 먼저 읽을 문서

1. [예선 평가항목](예선_평가항목.md): 심사 기준과 배점을 확인합니다.
2. 기획안: 현재 원본은 프로젝트 밖의 `C:/Users/hyjuy/Downloads/기획안.md`에 있습니다. 팀 공유용 사본은 아직 준비되지 않았습니다.
3. [PR 협업 기준](docs/PR_협업_기준.md): 브랜치, 검증, 리뷰 및 병합 방법을 확인합니다.
4. 공유 작업 상태에서 담당자, 진행 중인 작업, 브랜치와 선행 작업을 확인합니다.

## 작업별로 확인할 폴더

| 작업 | 확인할 폴더 | 내용 |
|---|---|---|
| 웹 화면·게임 UI | `frontend/src/`, `frontend/public/` | 화면 코드와 정적 자산 |
| API | `backend/app/api/` | 클라이언트와 서버 간 요청·응답 |
| 게임 진행·상태 | `backend/app/game/`, `backend/app/models/` | 상태, 규칙, 이벤트 및 데이터 모델 |
| AI NPC·평가 | `backend/app/agents/`, `backend/app/services/` | 에이전트와 관련 서비스 |
| 테스트 | `backend/tests/` | 백엔드 검증 코드 |
| 직무 기준·시나리오 | `data/ncs/`, `data/scenarios/`, `data/characters/`, `data/evaluation/` | NCS 자료, 사건, 인물, 평가 데이터 |
| 기획·조사 | `docs/planning/`, `docs/research/` | 기획 및 근거 조사 자료 |
| 검증·시연 | `docs/validation/`, `docs/demo/` | 검증 기록 및 시연 자료 |

현재 위 폴더들은 초기 구조이며 대부분 비어 있습니다. 작업 전 관련 폴더와 실제 연결된 코드를 확인하고, API나 게임 상태 형식을 변경할 때는 관련 담당자와 조율합니다. 기획안의 기술 선택과 NCS 코드는 아직 확정되지 않았습니다.

## 개발 계획과 시작 준비

- [3인 상세 개발 계획](docs/planning/3인_상세_개발_계획.md): 다직무 지원, 담당별 구현 순서와 검증 기준.
- [사람의 초기 준비](docs/planning/개발_시작_준비.md): 먼저 결정할 사항과 에이전트 실행 순서.
- 신규 직무 콘텐츠는 data/roles/<role_id>/에 구성할 예정입니다. 현재 게임 구현과 공통 계약은 아직 준비되지 않았습니다.
