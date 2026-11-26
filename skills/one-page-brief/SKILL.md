---
name: one-page-brief
description: 업무 책임자가 결정을 내릴 수 있도록 프로젝트, 실험, 프로토타입, AI 에이전트 검증 결과를 1페이지 핵심 보고로 작성하거나 줄인다. 사용자가 한 장짜리 업무 보고, 1페이지 핵심 보고, 의사결정용 검증 요약을 요청할 때 사용한다.
---

# 1페이지 핵심 보고

한 독자와 한 결정에 초점을 맞춘다. 자료에서 독자와 결정이 분명하면 그대로 쓰고, 그렇지 않으면 가정을 밝힌다. 이미 결정을 마친 일이라면 후속 검증이나 실행에서 필요한 판단을 첫머리에 둔다.

## 자료에서 근거 고르기

- 실제로 관찰한 현상, 원인 가설, 가상 시나리오를 구분한다. 결정을 바꿀 수 있는 근거를 최대 세 개 고르고, 조건과 관찰 결과 옆에 원문의 표, 테스트 ID, 로그 또는 링크를 둔다.
- 숫자가 판단을 좌우하면 초안 전에 원자료의 값, 기간, 단위, 분모, 비교 기준을 확인한다. 계산한 값은 식과 입력을 대조하고, 계산이나 반올림 기준이 바뀌면 연결된 결론도 다시 본다. 근거가 비어 있으면 [확인]과 확인 방법을 적는다.
- 구현, 개발 환경에서 확인한 기능, 실제 운영 효과를 각각 근거가 닿는 범위에서 설명한다. AI가 들어가면 맡긴 작업, 사람의 판단, 관찰한 출력 또는 차단 사례를 밝힌다. 결론을 바꾸는 미검증 항목은 본문에 남기고, 부가 확인 항목은 필요할 때 별첨에 둔다.

## 한 장에 쓰기

한국어 업무 보고는 짧은 항목과 일관된 종결 표현을 쓴다. 조직 양식이 있으면 그 형식을 따른다. 제목은 업무 또는 결정을 드러낸다.

1. **결론과 요청** — 처음 두 문장 안에 권고, 독자가 결정할 일과 결정이 필요한 이유를 적는다. 시점이나 지연 비용은 근거가 있을 때 넣는다.
2. **문제 정의** — 누가 어느 업무에서 무엇을 겪는지, 어떤 가설을 검증하는지 적는다. 여러 문제는 결정에 중요한 순서로 배치한다.
3. **문제 해결과 검증** — 각 문제에 대응하는 조치와 관찰 결과를 같은 순서로 붙인다. 선택이 필요하면 실행안과 현상 유지안을 포함해 근거 있는 대안을 동일한 효과, 비용, 위험 기준으로 비교한다. 수치가 없는 대안은 비교 범위를 밝힌다.
4. **결과 검토** — **사용 제한**에 근거의 적용 범위를 적는다. **앞으로 추진**에 담당 역할, 선행 조건, 실행 순서와 완료 기준을 둔다. 파일럿의 확대, 보류, 중단이 결정이라면 각각의 판단 조건을 적는다. 합의된 일정과 담당자만 확정 정보로 쓴다.

구두 브리핑을 요청하면 결론, 가장 중요한 근거, 요청을 담은 30초 분량의 말하기 문안을 별도로 작성한다.

## 최종 확인

- 독자가 원문을 열기 전에 결정과 이유를 이해할 수 있고, 주요 주장과 숫자는 근거로 되짚을 수 있는지 확인한다.
- 채팅과 Markdown은 짧은 문단과 목록으로 압축한다. 인쇄용은 지정 용지, 지정이 없으면 A4로 PDF를 내보내 실제 크기와 한 쪽 여부를 확인한다. PDF 페이지를 이미지로 열어 줄바꿈, 잘림, 글자 크기와 여백을 점검한다. 넘치면 중복과 부연을 줄이고 상세 표나 시각 자료를 별첨으로 옮긴다. 판단 근거와 적용 조건은 본문에 남긴다.

## 작업 사례와 벤치마킹

- 안전 결함 이관 테스트와 AI 요약의 적용 범위를 한 장으로 보고했다. [Aurora Owners 360 사례](https://github.com/jhheo51-arch/aurora-owners-360/blob/main/docs/CASE-SAFETY-VOC.md), [A4 예시 PDF](https://github.com/jhheo51-arch/jhheo51-arch/blob/5f4fc0f4f290f7e021950a861d73080812d7e563/skills/one-page-brief/examples/aurora-safety-voc-one-page-20261126-v2.pdf)
- 숫자를 계산하고 근거를 부여한 뒤 문장으로 옮기는 방식과, 목표 표본과 관찰 기간을 채울 때까지 확대 판단을 미루는 방식을 참고했다. [exec-brief-agent](https://github.com/jhheo51-arch/exec-brief-agent), [CRM LOOP](https://github.com/jhheo51-arch/crm-loop/blob/main/docs/CASE-REVISIT-DECISION.md)
- 한국어 보고 요지와 구두보고, 문제와 조치의 대응 순서, 한 쪽 렌더링 확인을 적용했다. [kr-work-report](https://github.com/mohitagw15856/pm-claude-skills/blob/04a88f1dd531f5afb152eddc67e0370eede6f288/skills/kr-work-report/SKILL.md), [one-pager-report](https://github.com/commetee12-source/one-pager-report-skill/blob/eabb884d986e04d55a46829334adae769887e5f1/SKILL.md)
- 원문에서 확인하지 못한 주장을 따로 추적하고, 필요할 때 현상 유지안과 비교하는 방식을 적용했다. [Executive Summary](https://github.com/SkillMedev/skills/blob/main/skills/executive-summary/SKILL.md), [Executive One-Pager](https://github.com/edwinjosechittilappilly/slipway/blob/15b03a54c141bf94fde314b4f2e74cdcc7f82727/skills/exec-one-pager/SKILL.md)
