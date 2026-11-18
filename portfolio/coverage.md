# UnityLoop 기능별 코드 대응

현재 표시되는 포폴의 System Design 사례 기준입니다.

| 구분 | 포폴 항목 | 대표 코드 | 범위 |
| --- | --- | --- | --- |
| 설계 사례 | 이슈 단위 단계 흐름과 판정 분리 | [issue-flow](issue-flow/README.md) | `state.py`의 단계 순서·재시도·되돌리기, `/issue` 종료 코드 규칙 발췌 · 서브에이전트 정의 미포함 |
| 설계 사례 | 훅 기반 쓰기 범위와 외부 쓰기 가드 | [hook-guard](hook-guard/README.md) | 훅 등록, 쓰기 범위·MCP·셸 훅, 하네스 시험 발췌 · 셸 구문 해석, 읽기·스킬 훅 본문 미포함 |
| 설계 사례 | CI 검증과 실패 원인 분류 | [ci-classify](ci-classify/README.md) | 워크플로 조각·점검, 실패 로그 분류와 그 시험 발췌 · 워크플로 조립·설치 미포함 |
