# SKH-Kit (결선판)

AI 코딩 에이전트 작업 규칙, 문서 뼈대, 사고 보조 스킬. 과제 결과물 코드는 포함하지 않음.

## 설치

    git clone https://github.com/DohunHyun/SKH-Kit /tmp/kit
    cat /tmp/kit/AGENTS.md >> AGENTS.md && mkdir -p docs .agents/skills && cp -n /tmp/kit/docs/*.md docs/ && cp -rn /tmp/kit/skills/. .agents/skills/

## 부르는 말

| 말 | 하는 일 | 언제 |
|---|---|---|
| 재정의 | 나를 인터뷰해 문제를 여러 렌즈로 다시 보기 | 시작 20~50분 |
| 질문 | 담당자에게 물을 질문 뽑기, 답 반영 | 재정의와 함께 |
| 데이터 | 데이터 함정 점검, 기준선 | 50~90분 |
| 레드팀 | 계획·결과를 네 시각으로 공격 | 중간 지점 |
| 피칭 | 3분 피칭 뼈대, 예상 질의 | 마지막 |
| handoff / 검증 / 복습 | 인수인계 / 성공 기준 확인 / 서술형 대비 | 기존과 동일 |

원칙: 내가 먼저 생각하고, AI는 비판하고 검증한다.
