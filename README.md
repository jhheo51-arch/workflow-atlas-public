# Workflow Atlas 공개판

Codex와 Claude Code로 반복하는 작업의 기준을 한곳에 모았습니다. 업무 범위 정리, 결과 검증, 의사결정 보고와 제안요청서 작성에 쓰는 스킬을 담았습니다.

| 스킬 | 언제 쓰나 | 남기는 결과 |
| --- | --- | --- |
| [작업 범위 정리](skills/scope-the-work/SKILL.md) | 요청이 넓거나 완료 조건이 모호할 때 | 바꿀 대상, 사용자가 할 수 있어야 하는 행동, 확인 방법 |
| [결과 전달 전 검증](skills/check-the-delivery/SKILL.md) | 수정본이나 시제품을 전달하기 직전 | 확인한 동작, 확인 환경, 남은 제한 |
| [1페이지 핵심 보고](skills/one-page-brief/SKILL.md) | 검증 결과를 한 장으로 보고하고 결정이 필요할 때 | 결론, 근거, 적용 범위와 다음 판단 조건 |
| [RFP 작성과 대응](skills/rfp/SKILL.md) | 제안요청서를 작성하거나 접수한 요청에 대응할 때 | 요구사항과 증빙, 평가 및 검수표, [OptiMesh 가상 예시](skills/rfp/examples/optimesh-rfp-20261126-v1.md) |

## 사용 방법

저장소에서 원하는 `SKILL.md`를 열어 도구에 읽혀도 됩니다. 프로젝트에서 계속 쓰려면 스킬 폴더 전체를 Codex의 `.agents/skills/` 또는 Claude Code의 `.claude/skills/`에 복사한 뒤 새 세션에서 해당 스킬을 선택하세요. [Codex 스킬 경로](https://developers.openai.com/api/reference/cli), [Claude Code 스킬 안내](https://code.claude.com/docs/en/skills)

예를 들어 `scope-the-work`로 “문의 양식을 짧게 만들어 주세요”를 검토하면, 어떤 항목에서 입력이 막히는지와 제출까지 확인할 조건을 먼저 정합니다. 수정 뒤 `check-the-delivery`로 모바일과 키보드에서 실제로 제출할 수 있는지 확인합니다.

## 출처와 확인 범위

범위 정리와 결과 검증은 공개 공통 지침에서 정리했습니다. 핵심 보고와 RFP는 기존 작업 사례를 바탕으로 공개 스킬의 방식을 참고했습니다. 출처와 적용 방식은 각 스킬에서 확인할 수 있습니다. [공개 공통 지침](https://github.com/jhheo51-arch/jhheo51-arch/blob/main/AGENTS.md)
