# 상위 버전 추적

본 프로젝트의 기반이 되는 상위 [agency-agents](https://github.com/msitarzewski/agency-agents) 버전을 기록하여 동기화 업데이트를 용이하게 합니다.

## 현재 베이스라인

- **상위 저장소**: https://github.com/msitarzewski/agency-agents
- **기준 commit**: `783f6a7` (2026-04-12)
- **상위 에이전트 총 수**: 184 (운영 문서 `strategy/` 16 개 제외)

## 번역 커버리지

| 카테고리 | 상위 수 | 번역 완료 | 커버리지 |
|----------|---------|-----------|----------|
| academic | 5 | 5 | 100% |
| design | 8 | 8 | 100% |
| engineering | 29 | 29 | 100% |
| finance | 5 | 5 | 100% |
| game-development | 20 | 20 | 100% |
| marketing | 30 | 30 | 100% |
| paid-media | 7 | 7 | 100% |
| product | 5 | 5 | 100% |
| project-management | 6 | 6 | 100% |
| sales | 8 | 8 | 100% |
| spatial-computing | 6 | 6 | 100% |
| specialized | 41 | 41 | 100% |
| support | 6 | 6 | 100% |
| testing | 8 | 8 | 100% |
| **합계** | **184** | **184** | **100%** |

> `strategy/` 디렉터리는 운영 문서 (playbooks / runbooks / 협업 템플릿) 이며, 상하위 콘텐츠가 동일하므로 에이전트 커버리지에 포함하지 않습니다.

## 번역 방법

상위 영어 원본 → 한국어 직역 (Claude Sonnet 일괄 번역). 원본 영어 README 의 어조와 구조를 보존하면서, 한국 기술 문체에 맞게 자연스러운 표현으로 옮겼습니다.

- 영어 기술 용어 (TensorFlow / PyTorch / RAG / MLOps / LLM / API / OAuth 등): 영어 그대로 유지
- 코드 블록, 파일 경로, URL, 명령어: 변경하지 않음
- 본문 / 헤딩 / 표 / 리스트: 자연스러운 한국어로 번역
- frontmatter `name:`, `description:`, `vibe:` 값: 한국어로 번역; `color:`, `emoji:`: 원본 유지

## 한국 시장 특화 에이전트

상위 184 개의 번역 외에, **한국 시장 특화 에이전트의 PR 을 환영**합니다. 다음과 같은 영역이 비어 있습니다:

- 플랫폼 운영 (KakaoTalk, Naver, LINE 등)
- 한국형 이커머스 (쿠팡, 11번가, 스마트스토어 등)
- 한국 기업 협업 도구 (카카오워크, 잔디, 라인웍스)
- 한국 컴플라이언스 (PIPA, 전자금융거래법, 금감원)
- 한국 시장 모바일 게임 / K-POP 팬덤 / 한국형 SaaS GTM

기여 방법은 [CONTRIBUTING.md](./CONTRIBUTING.md) 참조.

## 동기화 정책

- 상위 `main` 브랜치 추적
- 상위에서 신규 에이전트가 추가되면 순차적으로 번역
- 상위에 대규모 구조 변경 (디렉터리 이름 변경 등) 이 발생하면 1 주일 내 반영
- 상위 버전 번호는 동기화 시마다 본 파일에 업데이트
