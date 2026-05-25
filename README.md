# agency-agents 한국어판 (AI 에이전트 전문가팀)

🌐 **한국어** | [简体中文](https://github.com/jnMetaCode/agency-agents-zh) | [Português (BR)](https://github.com/jnMetaCode/agency-agents-pt-BR) | [Русский](https://github.com/jnMetaCode/agency-agents-ru) | [Bahasa Indonesia](https://github.com/jnMetaCode/agency-agents-id) | [العربية](https://github.com/jnMetaCode/agency-agents-ar) | [English (upstream)](https://github.com/msitarzewski/agency-agents)

> **184 개의 플러그앤플레이 AI 전문가 에이전트** — 엔지니어링, 디자인, 마케팅, 제품, 게임, 보안, 금융 등 18 개 부서를 포괄. 범용 프롬프트 템플릿이 아니라, 모든 에이전트는 독립적인 페르소나·전문 워크플로·산출물 정의를 갖춘다. Claude Code / Cursor / Copilot 등 17 종 AI 코딩 도구를 지원.

[agency-agents](https://github.com/msitarzewski/agency-agents) 의 한국어 커뮤니티판. 상위 184 개 에이전트의 전면 번역판이며, LINE / Naver / KakaoTalk / 쿠팡 / 라인 메신저봇 등 한국 시장 특화 에이전트는 **PR 환영**.

[![GitHub stars](https://img.shields.io/github/stars/jnMetaCode/agency-agents-ko?style=social)](https://github.com/jnMetaCode/agency-agents-ko)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)


### 📊 프로젝트 규모

| 🤖 AI 에이전트 | 🌏 상위 번역 | 🇰🇷 한국 시장 원본 | 🧠 지원 도구 | 🏢 부서 |
|:---:|:---:|:---:|:---:|:---:|
| **184** | **184** | **PRs welcome** | **17 종** | **18 개** |

> 📖 **Companion reading (中文 / Chinese)**: [《AI 编程实战 · 방법론 3 권 시리즈》](https://book.aibuzhiyu.com/) — 10 종 AI 코딩 도구 완전 가이드 + 실전 경험. 본 저장소의 184 개 에이전트를 Claude Code / Cursor / Codex 에 설치한 뒤 방법론과 함께 사용하면 효율이 배가된다. 온라인 도서 + PDF · 영구 무료 · *(중국어로 작성됨)*

---

## 🚀 Agency Orchestrator — 에이전트 라이브러리를 실제로 가동시킨다

> **💡 한 문장으로 다수의 AI 전문가가 자동 협업하여 몇 분 만에 완전한 결과물을 산출.**
>
> 에이전트 라이브러리가 전문가를 제공한다면, [**Agency Orchestrator**](https://github.com/jnMetaCode/agency-orchestrator) 는 그 전문가들을 실제 팀처럼 협업시킨다.

```bash
npm install -g agency-orchestrator
ao compose "AI Agent 에 대한 심층 분석 글을 작성해 줘" --run
```

```
🎭 자동 캐스팅 → 서사학자 + 심리학자 + 콘텐츠 크리에이터 + 내러티브 디자이너
📊 자동 오케스트레이션 → DAG 워크플로, 의존성 자동 감지, 병렬 실행
✅ 자동 산출 → 몇 분 후 완성된 결과물 확보
```

| 기능 | 설명 |
|:---|:---|
| 🎯 **노코드 오케스트레이션** | 순수 자연어 또는 YAML, 한 문장으로 요구사항 기술 |
| ⚡ **DAG 병렬 실행** | 의존성 자동 감지, 의존성 없는 단계는 병렬 실행으로 속도 2 배 |
| 🔄 **체크포인트 재개** | 실패한 단계만 단독 재실행 가능, 처음부터 다시 할 필요 없음 |
| 🆓 **6 종 무료 LLM** | Claude Code / Gemini CLI / Copilot / Codex / OpenClaw / Ollama |
| 💰 **3 종 API 연동** | DeepSeek / Claude API / OpenAI |
| 📋 **32 개 즉시 사용 가능한 템플릿** | 개발, 마케팅, 데이터 분석, 디자인, 운영 등 |

<p align="center">
  <a href="https://github.com/jnMetaCode/agency-orchestrator">
    <strong>⭐ Agency Orchestrator 살펴보기 — 184 개 에이전트의 협업을 →</strong>
  </a>
</p>

---

## 이것은 무엇인가?

**즉시 사용 가능한 AI 에이전트 라이브러리** 한 세트. 각 에이전트는 명확한 정체성, 핵심 규칙, 워크플로, 산출물 정의를 갖추고 있으며, AI 코딩 도구에 설치한 뒤 자연어로 활성화할 수 있다.

**일반 프롬프트와의 차이점**: 일반 프롬프트는 AI 에게 "당신은 전문가입니다" 라고만 알려주지만, 여기의 에이전트들은 그 전문가가 **어떻게 사고하고, 어떻게 일하며, 무엇을 산출하는지**까지 정의한다. 예를 들어 [보안 엔지니어](engineering/engineering-security-engineer.md)는 OWASP Top 10 기준으로 코드를 항목별 점검하고, [프론트엔드 개발자](engineering/engineering-frontend-developer.md)는 React 컴포넌트를 ARIA / 접근성 / 성능 예산 기준으로 리팩토링한다.

---

## 빠른 시작

### 방법 1: AI 도구에 원클릭 설치

**17 종의 주요 AI 코딩 도구**를 지원하며, 한 줄의 명령으로 끝낸다:

```bash
# 설치된 도구를 자동 감지하여 일괄 설치
./scripts/install.sh

# 또는 특정 도구를 지정해 설치
./scripts/install.sh --tool openclaw       # OpenClaw ⭐ 추천
./scripts/install.sh --tool claude-code    # Claude Code
./scripts/install.sh --tool copilot        # GitHub Copilot
./scripts/install.sh --tool cursor         # Cursor
./scripts/install.sh --tool kiro           # Kiro (Amazon)
./scripts/install.sh --tool trae           # Trae
./scripts/install.sh --tool opencode       # OpenCode
./scripts/install.sh --tool aider          # Aider
./scripts/install.sh --tool windsurf       # Windsurf
./scripts/install.sh --tool antigravity    # Antigravity
./scripts/install.sh --tool gemini-cli     # Gemini CLI
./scripts/install.sh --tool qwen           # Qwen Code
./scripts/install.sh --tool codex          # Codex CLI
./scripts/install.sh --tool deerflow       # DeerFlow 2.0 (ByteDance)
./scripts/install.sh --tool workbuddy      # WorkBuddy (Tencent)
./scripts/install.sh --tool hermes         # Hermes Agent (NousResearch)
./scripts/install.sh --tool qoder          # Qoder
```

> Claude Code 와 GitHub Copilot 은 직접 설치 가능; 그 외 도구는 먼저 `./scripts/convert.sh` 로 포맷 변환이 필요하다.

### 🔥 OpenClaw 사용자 퀵스타트

OpenClaw 는 현재 커뮤니티 사용자가 가장 많은 통합 방식이다. 각 에이전트는 세 개의 파일로 분리된다: `SOUL.md` (정체성 페르소나) + `AGENTS.md` (업무 역량) + `IDENTITY.md` (요약). 다중 에이전트 협업 오케스트레이션을 기본 지원한다.

```bash
./scripts/convert.sh --tool openclaw   # 1 단계: SOUL.md 포맷으로 변환
./scripts/install.sh --tool openclaw   # 2 단계: ~/.openclaw/ 에 설치
```

설치 후 OpenClaw 게이트웨이를 재시작하면 바로 사용 가능.

### 방법 2: 수동 복사

```bash
# Claude Code / GitHub Copilot (직접 복사)
cp -r engineering/*.md ~/.claude/agents/

# Claude Code 에서 활성화:
# "프론트엔드 개발자 모드를 활성화해서 React 컴포넌트를 만들어 줘"
```

### 방법 3: 프롬프트 참고 자료로 활용

[CATALOG.md](CATALOG.md) 에서 에이전트 목록을 훑어보고 필요한 부분을 복사/각색해 쓰면 된다.

---

## 에이전트 라인업

전체 184 개 에이전트의 상세 카탈로그는 **[CATALOG.md](CATALOG.md)** 참조. 부서별 요약은 아래와 같다.

| 부서 | 에이전트 수 | 대표 역할 |
|------|-------------|-----------|
| 🛠️ 엔지니어링 | 29 | 프론트엔드, 백엔드 아키텍트, AI 엔지니어, DevOps, 보안, SRE, 임베디드, FPGA |
| 🎨 디자인 | 8 | UI/UX 디자이너, 브랜드 가드, 이미지 프롬프트 엔지니어, 비주얼 스토리텔러 |
| 📢 마케팅 | 30 | 그로스 해커, 콘텐츠 크리에이터, SEO, TikTok / Twitter / Instagram / Reddit 전략가 |
| 💰 페이드 미디어 | 7 | 광고 감사, 크리에이티브, PPC, 프로그래매틱 매입, 트래킹 어트리뷰션 |
| 💼 세일즈 | 8 | 어카운트 전략가, 세일즈 코치, MEDDPICC 딜 전략가, 아웃바운드, 파이프라인 분석 |
| 🏦 금융 | 5 | 회계 컨트롤러, FP&A 분석가, 투자 리서처, 사기 탐지 |
| 👔 인사 | — | (한국 시장 특화 PRs welcome) |
| ⚖️ 법무 | — | (한국 시장 특화 PRs welcome) |
| 🚚 공급망 | — | (한국 시장 특화 PRs welcome) |
| 📦 제품 | 5 | 제품 매니저, 피드백 시너시저, 트렌드 리서처, 우선순위 책정자 |
| 📋 프로젝트 관리 | 6 | 스튜디오 프로듀서, 익스페리먼트 트래커, 프로젝트 시퍼 |
| 🧪 테스팅 | 8 | 테스트 자동화 엔지니어, API 테스터, 퍼포먼스 벤치마커, 리얼리티 체커 |
| 🤝 고객 지원 | 6 | 인시던트 커뮤니케이터, 고객 인사이트 익스트랙터 |
| 🔬 스페셜티 | 41 | 블록체인 보안 감사, 컴플라이언스 (SOC 2, ISO 27001, HIPAA), 법률 문서 리뷰, 부동산, HR 온보딩 등 |
| 🥽 공간 컴퓨팅 | 6 | XR 사용자 연구, AR/VR 엔지니어, 햅틱 디자이너 |
| 🎮 게임 개발 | 20 | Unity 아키텍트, Unreal 아키텍트, Godot, Roblox, Blender, 게임 디자인, 멀티플레이어 |
| 📖 학술 | 5 | 인류학자, 심리학자, 역사학자, 서사학자, 지리학자 |

---

## 도구 통합

### 지원 도구

| 도구 | 설치 위치 | 비고 |
|------|-----------|------|
| **Claude Code** | `~/.claude/agents/` | 직접 사용 가능 (변환 불필요) |
| **GitHub Copilot** | `.github/agents/` | 직접 사용 가능 |
| **OpenClaw** | `~/.openclaw/` | SOUL.md / AGENTS.md / IDENTITY.md 3 파일 분할 ⭐ |
| **Cursor** | `.cursor/rules/` | `.mdc` 규칙 파일로 변환 |
| **Aider** | `CONVENTIONS.md` | 단일 컨벤션 파일로 컴파일 |
| **Windsurf** | `.windsurfrules` | 단일 규칙 파일로 컴파일 |
| **Trae** | `.trae/agents/` | Trae 에이전트 포맷 |
| **OpenCode** | `.opencode/agents/` | OpenCode 포맷 |
| **Codex CLI** | `.codex/agents/` | TOML 포맷 |
| **Kiro (Amazon)** | `~/.kiro/agents/` | JSON 설정 + 프롬프트 파일 |
| **Gemini CLI** | `~/.gemini/agents/` | Gemini 포맷 |
| **Qwen Code** | `~/.qwen/agents/` | Qwen 포맷 |
| **Antigravity** | `~/.antigravity/agents/` | Antigravity 포맷 |
| **DeerFlow 2.0** | `skills/custom/` | ByteDance SuperAgent SKILL.md |
| **WorkBuddy** | `~/.workbuddy/skills/` | Tencent 데스크톱 에이전트 |
| **Hermes Agent** | `~/.hermes/skills/` | NousResearch 오픈소스 프레임워크 |
| **Qoder** | `~/.qoder/agents/` | Markdown + YAML frontmatter |

### 사용 방법

설치 후 AI 도구에서 자연어로 활성화한다:

```
"보안 엔지니어 모드를 활성화해서 이 API 엔드포인트를 점검해 줘"
"AI 엔지니어 역할로 RAG 파이프라인을 설계해 줘"
"DevOps 자동화 엔지니어로서 Kubernetes 매니페스트를 만들어 줘"
```

각 도구별 상세 설치 가이드는 `integrations/` 디렉터리 참조.

### 에이전트 수정 후 재생성

새 에이전트를 추가하거나 기존 에이전트를 편집한 후 통합 파일을 재생성:

```bash
./scripts/convert.sh               # 모든 도구 재생성
./scripts/convert.sh --tool cursor # 특정 도구만 재생성
```

---

## 🇰🇷 한국 시장 특화 에이전트 — PRs Welcome

상위 184 개 에이전트의 번역은 완료되었으며, 다음과 같은 한국 시장 특화 에이전트의 PR 을 환영합니다:

- **플랫폼 운영**: KakaoTalk 비즈니스 채널, 네이버 블로그 / 카페 / 지식인 운영, 인스타그램 한국 마켓, 유튜브 한국 채널, 라인 메신저봇
- **이커머스**: 쿠팡 셀러, 11번가, 스마트스토어, 무신사, 마켓컬리 운영
- **기업 협업**: 카카오워크, 잔디 (JANDI), 라인웍스 통합 개발
- **금융 / 정부**: 한국 금감원 컴플라이언스, 개인정보보호법 (PIPA), 전자금융거래법 대응
- **수직 영역**: 한국형 SaaS GTM, 한국 시장 모바일 게임 운영, K-POP 팬덤 마케팅

기여 방법은 [CONTRIBUTING.md](CONTRIBUTING.md) 참조.

---

## 실전 사례

### 시나리오 1: 글로벌 MVP 출시

**당신의 팀**:
1. **프론트엔드 개발자** — React 앱 구축
2. **백엔드 아키텍트** — API 및 데이터베이스 설계
3. **그로스 해커** — 사용자 확보 전략 수립
4. **래피드 프로토타이퍼** — 빠른 반복
5. **리얼리티 체커** — 출시 전 품질 게이트

### 시나리오 2: 보안 감사 + 컴플라이언스

**당신의 팀**:
1. **보안 엔지니어** — OWASP Top 10 코드 점검
2. **블록체인 보안 감사** (해당 시) — 스마트 컨트랙트 취약점 분석
3. **컴플라이언스 감사** — SOC 2 / ISO 27001 / HIPAA 준수 점검
4. **인시던트 커뮤니케이터** — 발견된 위험 사항을 경영진에 전달
5. **테크니컬 라이터** — 감사 보고서 문서화

---

## 기여

번역, 콘텐츠 개선, 한국 시장 특화 에이전트 신규 추가 모두 환영합니다. 자세한 가이드는 [CONTRIBUTING.md](CONTRIBUTING.md) 참조.

---

## 자매 프로젝트

| 프로젝트 | 포지셔닝 | 한 줄 소개 |
|----------|----------|------------|
| **본 프로젝트** (agency-agents-ko) | 🎭 한국어판 에이전트 라이브러리 | 184 개 **즉시 사용 가능한** AI 전문가, 한국 시장 특화 PRs welcome |
| [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) ![](https://img.shields.io/github/stars/jnMetaCode/agency-agents-zh?style=flat&label=⭐) | 🇨🇳 중국어판 | 215 개 (165 번역 + 50 중국 시장 원본 — 샤오홍슈 / 더우인 / 페이슈 / 딩딩 / Qt HMI / 기계 설계) |
| [agency-agents-pt-BR](https://github.com/jnMetaCode/agency-agents-pt-BR) | 🇧🇷 포르투갈어판 (브라질) | 184 개 번역된 에이전트 |
| [agency-agents-ru](https://github.com/jnMetaCode/agency-agents-ru) | 🇷🇺 러시아어판 | 184 개 번역된 에이전트 |
| [agency-agents-id](https://github.com/jnMetaCode/agency-agents-id) | 🇮🇩 인도네시아어판 | 184 개 번역된 에이전트 |
| [agency-agents-ar](https://github.com/jnMetaCode/agency-agents-ar) | 🇸🇦 아랍어판 | 184 개 번역된 에이전트 |
| [agency-agents](https://github.com/msitarzewski/agency-agents) | 🌏 영문 상위 (Upstream) | 184 개 원본 에이전트 — 이 프로젝트의 베이스 |
| [agency-orchestrator](https://github.com/jnMetaCode/agency-orchestrator) | 🚀 오케스트레이션 엔진 | 한 문장 → 184 명 전문가 협업, **몇 분 안에 결과 산출** (9 LLM / 6 무료) |

---

## 감사의 글

- 영문 원본: [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) (MIT 라이선스)
- 원저자 [@msitarzewski](https://github.com/msitarzewski) 께서 만들어 주신 훌륭한 프로젝트에 감사드립니다
- 한국어 번역은 Claude Sonnet 으로 일괄 번역한 뒤 검토를 거쳤습니다. 표현 개선 PR 은 언제든지 환영합니다.

---

## 라이선스

MIT License — 상업적 / 개인적 용도 모두 자유롭게 사용 가능.

---

<div align="center">

**184 개 AI 전문가 에이전트, 17 종 도구 지원, 즉시 설치 사용**

[⭐ Star 본 프로젝트](https://github.com/jnMetaCode/agency-agents-ko) · [Issue 제출](https://github.com/jnMetaCode/agency-agents-ko/issues) · [코드 기여](https://github.com/jnMetaCode/agency-agents-ko/pulls)

[agency-agents](https://github.com/msitarzewski/agency-agents) 를 기반으로 번역 및 한국 시장 현지화

</div>
