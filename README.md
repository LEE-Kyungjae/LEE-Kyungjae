<div align="center">

# Kyungjae Lee

### Agentic Systems · Backend Engineering · Developer Tools

AI가 답하는 데서 끝나지 않고, 근거를 남기고 도구를 실행하며<br />
운영 결과로 검증되는 시스템을 만듭니다.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/LEE-Kyungjae)
[![Portfolio](https://img.shields.io/badge/Portfolio-0F766E?style=flat-square&logo=githubpages&logoColor=white)](https://LEE-Kyungjae.github.io)
</div>
<div align="center">
<br />
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=future_nkrcb)](https://solved.ac/sty14/)
</div>
---

## Engineering focus

```text
Intent & context
       ↓
Judgment & approval
       ↓
Execution & observation
```

- **Agent architecture** — 실행 이력, 도구 정책, 승인, 복구까지 포함하는 통제 가능한 에이전트 런타임
- **Backend engineering** — 외부 서비스와 데이터를 안정적으로 연결하는 운영 중심의 백엔드
- **Developer tools** — 반복되는 개발 과정을 줄이고 판단 과정을 추적할 수 있는 자동화 도구

## Systems I build

### [Palamedes](https://github.com/LEE-Kyungjae/Palamedes) · Autonomous AI pre-planner

실행 전에 임무를 발견하고, 경쟁 가설과 반증 조건을 세우며, 계획의 변경·복원을 추적하는 planning kernel입니다. 멀티 에이전트 provenance, stale-world protection, bounded context를 통해 AI의 판단 과정을 검사하고 재현할 수 있게 설계했습니다.

`Python` `TypeScript` `Multi-agent systems` `State & provenance` `Contract tests`

### [GahyeonBot](https://github.com/LEE-Kyungjae/gahyeonbot) · AI agent assistant

Discord 텍스트와 음성을 하나의 에이전트 런타임으로 연결한 실사용 비서입니다. 영속 session/run/event 원장, bounded tool loop, 읽기·승인·거부 정책, 중복 실행 방지, 백그라운드 작업 복구를 구현했습니다. VAD → STT → LLM → TTS 음성 파이프라인과 지식·날씨 도구도 함께 운영합니다.

`Java 21` `Spring Boot` `PostgreSQL` `JDA` `Voice AI` `Blue/Green deployment`

## How I work

- 데모 기능보다 **실패 이후에도 복구 가능한 운영 흐름**을 먼저 설계합니다.
- AI의 결과뿐 아니라 **판단 근거, 실행 이력, 승인 경계**를 시스템에 남깁니다.
- 코드, 데이터, 배포를 따로 보지 않고 **관측 가능한 하나의 제품 흐름**으로 연결합니다.
- 반복 작업은 자동화하되, 위험한 변경에는 사람이 개입할 수 있는 제어면을 둡니다.

## Core stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<details>
<summary><b>GitHub activity</b></summary>
<br />

<p align="center">
  <img width="49%" src="https://raw.githubusercontent.com/LEE-Kyungjae/github-stats/master/generated/overview.svg#gh-dark-mode-only" alt="Kyungjae Lee GitHub overview" />
  <img width="49%" src="https://raw.githubusercontent.com/LEE-Kyungjae/github-stats/master/generated/languages.svg#gh-dark-mode-only" alt="Kyungjae Lee language statistics" />
</p>

</details>

---

<div align="center">
  <sub>Build systems that can explain, execute, and recover.</sub>
</div>
