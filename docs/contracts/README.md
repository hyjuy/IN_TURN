# 공유 계약 초안

이 문서는 구현 전 합의가 필요한 초안이다. 담당자 리뷰 후 확정한다.

## 게임 세션

`session_id`, `role_id`, `content_version`, `version`, `day`, `current_event_id`, `stats`, `relationships`, `flags`, `status`를 포함한다.

## 작업자 간 원칙

- 서버가 선택 가능 여부, 상태 변화와 날짜 진행을 검증한다.
- 각 요청·응답의 JSON 예시와 오류 형식은 구현 담당자들이 이 문서에 추가한다.
- 행동 기록은 고유 ID와 세션·사건을 참조하고 보고서 근거는 행동 ID를 연결한다.
- 직무 콘텐츠는 `data/roles/<role_id>/`에 두고 세션 시작 시 콘텐츠 버전을 고정한다.

## 미확정

정확한 필드 타입, API 경로, 오류 응답, 콘텐츠 JSON 스키마는 1·2·3번 담당자가 합의해야 한다.
