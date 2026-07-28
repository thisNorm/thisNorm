<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=230&color=gradient&text=Norm%20%7C%20Backend%20Engineer&fontAlign=50&animation=fadeIn&fontColor=ffffff&fontSize=50&desc=Edge%20Systems%20%C2%B7%20Data%20Pipelines%20%C2%B7%20Applied%20AI&descAlign=50&descSize=18)

### Code with Rhythm, Ship with Impact! 🎶

새로운 기술을 유행어로 소비하기보다,  
**직접 동작하는 서비스로 구현해 사용 조건과 한계를 확인하는 백엔드 엔지니어 황규범(Norm)**입니다.

스마트팜 엣지 서버, 실시간 데이터 파이프라인, 온디바이스 AI, 멀티 에이전트와 자동화까지  
현실의 제약 속에서 기술이 실제로 어디까지 유효한지 검증하는 것을 좋아합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-thisnorm.dev-20B2F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://thisnorm.dev)
[![Tech Blog](https://img.shields.io/badge/Tech_Blog-thisnorm.tistory.com-FF5722?style=for-the-badge&logo=tistory&logoColor=white)](https://thisnorm.tistory.com)
[![Email](https://img.shields.io/badge/Email-kisook2557%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kisook2557@gmail.com)

</div>

---

## 👋 About Me

현재 **인포벨리코리아 백엔드 엔지니어**로 스마트팜 엣지 서버와 현장 데이터 파이프라인을 개발하고 있습니다.

- **Edge & IoT Backend** — 네트워크·PC·디바이스 세팅부터 서버 연동, 데이터 수집과 장애 진단까지 현장 운영 전 구간을 다룹니다.
- **Reliable Data Pipeline** — Redis Queue, DLQ, 프록시 모듈을 활용해 통신 장애와 일시적인 서버 중단에도 데이터를 보존합니다.
- **Constraint-driven Architecture** — 폐쇄망, 모바일 OS 보안 제약, 실시간 스트리밍 부하처럼 환경에서 비롯되는 문제를 구조적으로 해결합니다.
- **Applied AI** — 온디바이스 AI, 로컬 LLM, 멀티 에이전트와 자동화를 작은 제품으로 구현하고 비용·품질·운영 가능성을 판단합니다.

> **Curiosity → Prototype → Operation → Reflection**  
> 궁금한 기술을 직접 구현하고, 잘된 점뿐 아니라 실패 조건과 다음 개선점까지 기록합니다.

---

## 🏆 Signature Projects

### 1. DeepVoice Shield · 실시간 딥보이스 탐지 및 보이스피싱 예방

처음으로 팀원들과 약 1년간 개발한 장기 프로젝트이자, 가장 많은 시행착오와 수상 경험을 남긴 프로젝트입니다.

- 클라우드 추론 지연과 Android 통화 음성 접근 제약을 해결하기 위해 **온디바이스 AI 중심으로 아키텍처 전환**
- Pruning, INT8 Quantization, 1채널 입력 구조를 적용해 모델을 약 **91% 경량화**
- 기본 전화 통화 대신 자체 VoIP·P2P 통신 파이프라인을 구축해 실시간 탐지 흐름 구현
- 모바일 앱, 백엔드 API, 웹 체험 페이지, AI 알고리즘을 독립 모듈로 구성
- 디지털 바이오헬스 경진대회 대상, 충청권 ICT 이노베이션스퀘어 대상 등 다수 수상

| Component | Repository | Main Tech |
| :--- | :--- | :--- |
| Backend | [deepfake_detection_service_backend](https://github.com/thisNorm/deepfake_detection_service_backend) | `NestJS` `Socket.io` `AWS EC2/S3` |
| Mobile | [deepfake_detection_service_application](https://github.com/thisNorm/deepfake_detection_service_application) | `React Native` `Android` `TFLite` |
| Algorithm | [deepfake_detection_service_algorithm](https://github.com/thisNorm/deepfake_detection_service_algorithm) | `PyTorch` `ONNX` `TFLite` |
| Frontend | [deepfake_detection_service_frontend](https://github.com/thisNorm/deepfake_detection_service_frontend) | `React` `Vite` |

### 2. [content-agent](https://github.com/thisNorm/content-agent) · 개인 콘텐츠 운영 자동화

수업 내용을 Notion에 정리한 뒤 블로그와 SNS에 다시 가공해 올리는 일을 꾸준히 하기 어려워 만든 **개인용 콘텐츠 자동화 파이프라인**입니다.

- Notion 페이지 링크 하나로 본문 파싱, 글 각색, 썸네일 생성, Tistory 발행, X 포스팅까지 자동 처리
- 규칙 기반 변환과 AI 작업을 분리해 불필요한 토큰 사용을 줄이고 결과 검증 가능성 확보
- Playwright 발행, 이미지 합성, 실행 로그 기록, Dry-run과 fail-closed 흐름 구현
- 향후 음성 기록을 구조화한 뒤 같은 파이프라인으로 연결하는 확장 가능성 확인

`TypeScript` `Notion API` `Claude API` `Gemini Image` `Playwright` `Tistory` `X API`

**What I learned**  
개인 자동화는 거대한 플랫폼보다, 반복적으로 미루게 되는 한 가지 불편을 끝까지 연결했을 때 가장 실용적이었습니다.

---

## 🧪 Applied Systems & Technical Experiments

아래 프로젝트들은 당시 대두되던 기술 키워드를 직접 구현하며 **어디에 유효하고 무엇이 부족한지 확인한 PoC 및 탐색 프로젝트**입니다.

### [AegisView / Lab Guardian](https://github.com/thisNorm/lab-guardian) · 폐쇄망 AI 통합 관제

ETRI 인턴 기간에 사용할 수 있던 CCTV, 이동형 로봇과 GPU 서버를 활용해 만든 실시간 관제 시스템입니다.

- YOLOv8 기반 고정형 카메라·이동형 로봇 영상 통합
- AI 연산은 Python/FastAPI, 이벤트 저장과 브로드캐스트는 C# Gateway로 분리
- Redis Queue·DLQ, SQLite 메타데이터 저장, WebSocket 대시보드, 스냅샷·녹화·알림 구현

**What I learned**  
객체가 겹칠 때 발생하는 Tracker ID Switch와 카메라 스트림 증가에 따른 디코딩·추론·전송 비용을 함께 고려해야 실제 다중 카메라 관제로 확장할 수 있습니다. 기능 구현 이후에는 자원 예산, 프레임 샘플링, 추적 안정성 설계가 더 중요해졌습니다.

`Python` `FastAPI` `YOLOv8` `.NET 8` `Redis` `SQLite` `WebSocket` `React`

### [SiteOps Radar](https://github.com/thisNorm/siteops-radar) · SEO·AEO·GEO 사이트 분석

여러 웹사이트를 만들며 SEO의 중요성을 느낀 뒤, AEO와 GEO라는 개념이 등장하자 기존 웹 품질 분석에 함께 적용해 본 프로젝트입니다.

- 성능, SEO, 보안, 접근성과 AEO/GEO 준비도를 한 화면에서 분석
- PageSpeed 데이터, 규칙 기반 점수, 경쟁 사이트 차이, AI 요약을 결합
- Prisma/PostgreSQL 영속화와 Vitest·Playwright 기반 테스트 구성

**What I learned**  
SEO와 달리 AEO·GEO는 아직 보편적으로 합의된 평가 틀이 명확하지 않았습니다. 따라서 단정적인 최적화 점수보다는 콘텐츠 구조, 인용 가능성, 기계 가독성 같은 **준비도 신호를 제공하는 보조 지표**로 다루는 편이 적절하다고 판단했습니다.

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Gemini` `Vitest` `Playwright`

### [Combat Power Analyzer](https://github.com/thisNorm/combat-power-analyzer) · GraphQL 기반 GitHub 캐릭터 분석

업무에서 MQTT, HTTP API와 MCP 등 여러 통신 방식을 접하며, GraphQL이 어떤 상황에서 유용한지 확인하기 위해 만든 프로젝트입니다.

- GitHub REST API 데이터를 수집해 개발자의 활동을 RPG 캐릭터 능력치로 변환
- Apollo Server·Client 기반 GraphQL 단일 엔드포인트 구성
- Redis 캐시와 API 방어 로직, AI 기반 캐릭터 설명, 이미지 저장과 SNS 공유 구현

**What I learned**  
GraphQL은 모든 REST API를 대체하기보다, 화면마다 필요한 데이터 형태가 다르고 여러 테이블·데이터 소스에서 중첩된 일부 필드만 선택해야 할 때 특히 유용했습니다. 반대로 단순 CRUD에서는 스키마와 Resolver 관리 비용도 함께 고려해야 합니다.

`Next.js` `GraphQL` `Apollo` `Redis` `GitHub API` `Gemini` `html2canvas`

### [Agent Office](https://github.com/thisNorm/agent-office) · 멀티 에이전트 가상 팀 실험

여러 AI 에이전트를 실제 팀처럼 구성해 업무를 나누는 사례가 확산되던 시기에, 역할 기반 에이전트와 가상 오피스 UI를 구현해 본 실험입니다.

- 역할별 에이전트 응답과 멘션 기반 대화 흐름 구성
- 에이전트 상태, 이동과 대화를 사무실 형태의 UI로 시각화
- 팀 단위 AI 워크플로우의 사용 경험과 운영 조건 탐색

**What I learned**  
멀티 에이전트의 품질은 모델 성능과 추론 비용에 크게 좌우됩니다. 비용을 제한하면 역할만 여러 개로 나눈다고 결과가 좋아지지 않았고, 장기간 사용할 팀으로 만들려면 강한 로컬 LLM 또는 효율적인 모델 라우팅과 함께 Obsidian·NotebookLM처럼 지속되는 공유 기억 구조가 필요했습니다.

`Multi-Agent` `Role-based Workflow` `LLM` `Interactive UI`

### [Air-gapped AutoCI](https://github.com/thisNorm/Air-gapped_DevOps) · 폐쇄망 CI/CD 자동화 PoC

AI 기반 CI/CD 자동화 교육을 들은 뒤, 클라우드 AI를 사용할 수 없는 ETRI와 같은 폐쇄망에서도 자동화가 가능한지 검증한 프로젝트입니다.

- 자연어 요구사항을 GitLab CI YAML 초안으로 변환
- GitLab CE·Runner, 로컬 LLM과 Docker Compose를 활용한 폐쇄망 재현
- Docker 네트워크 제한과 Sandbox 안에서 구조·안전성 검사 및 Smoke Test 수행
- 검증을 통과한 결과를 GitLab 파이프라인으로 연결

**What I learned**  
이 구조는 로컬 LLM, GitLab과 Docker 사용이 허용된다는 전제가 필요합니다. 소형 로컬 모델은 자유 형식 YAML을 안정적으로 생성하지 못했기 때문에, 모델에는 요구사항 분류만 맡기고 검증된 템플릿과 Sandbox 검사를 결합하는 방식이 더 현실적이었습니다. 더 높은 품질을 위해서는 프로젝트별 YAML 데이터셋을 활용한 튜닝이나 더 강한 로컬 모델이 필요합니다.

`GitLab CI/CD` `GitLab Runner` `Local LLM` `Docker Sandbox` `FastAPI` `Smoke Test`

---

## 💼 Professional Experience

### 주식회사 인포벨리코리아 · Backend Engineer
`2026.06 — Present` · 스마트팜 엣지 서버 / 현장 인프라

- 스마트팜 클라우드 서비스의 **엣지 서버 및 데이터 파이프라인 아키텍처** 설계·개발
- 소리 수집기, 비콘 등 다중 하위 모듈의 유기적 동작을 위한 오케스트레이션과 모듈 단위 고립 테스트 체계 도입
- 프록시 모듈과 Redis를 활용한 **엣지–클라우드 데이터 유실 방지 구조** 구축
- 현장 네트워크 구성, 서버·PC 세팅, 디바이스 통신 연동과 장애 진단 수행

`Node.js` `JavaScript` `Redis` `SQLite` `Linux` `Docker` `Networking` `IoT`

### 한국전자통신연구원(ETRI) 자율형 IoT 연구실 · Research Intern
`2026.01 — 2026.02` · AI 기반 폐쇄망 통합 관제

- CCTV와 이동형 로봇을 통합한 AI 객체 탐지·원격 대응 시스템 설계
- Redis Queue와 DLQ를 적용한 비동기 이벤트 처리 및 장애 복구 구조 구축
- 카메라 스트리밍, 객체 탐지, 원격 제어, 이벤트 저장 파이프라인 통합

`Python` `FastAPI` `.NET 8` `Redis` `SQLite` `WebSocket` `YOLOv8` `OpenCV`

---

## 🏅 Honors & Awards

| Award | Organization | Date |
| :--- | :--- | :---: |
| 🎖 **총장상** — 교내외 기술 성과를 통한 학교 명예 기여 | 홍익대학교 | 2026.01 |
| 🏆 **대상** — 디지털 바이오헬스 종합설계 경진대회 | 홍익대학교 바이오헬스 혁신융합대학 | 2025.12 |
| 🏆 **대상** — 충청권 ICT 이노베이션스퀘어 S/W 개발 분과 | 과학기술정보통신부 · 세종테크노파크 | 2025.11 |
| 🥈 **우수상** — 지역혁신 인재양성 연합 페스티벌 | 한국정보통신보안윤리학회 | 2025.11 |
| 🥇 **최우수상** — OpenCV Zoo 기반 영상분석 실무 프로젝트 | 홍익대학교 산학협력단 | 2025.09 |

---

## 🛠 Tech Stack

<div align="center">

**Backend & Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Data, Infra & Communication**

![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

**AI, Vision & Automation**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![On-device AI](https://img.shields.io/badge/On--device_AI-6A5ACD?style=flat-square)
![Local LLM](https://img.shields.io/badge/Local_LLM-222222?style=flat-square)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Workflow-74AA9C?style=flat-square)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automation-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

</div>

---

## 🎓 Education, Research & Certifications

### Hongik University, Sejong

- **Software Convergence** — Major
- **Big Data Business** — Convergence Major
- `2020.03 — 2026.08 (Expected)`

### Research

- **폐쇄망 환경을 위한 AI 객체 인식 기반 고정형·이동형 카메라 통합 관제 시스템**
- **메타버스 환경의 딥보이스 탐지 방법 연구**

### Certifications

- **AI-POT 프롬프트 엔지니어링 1급** · 2026.02
- **정보처리기사 필기 합격** · 2025.08
- **SQLD** · 2024.09

---

## 📂 Other Project

| Project | Description | Tech |
| :--- | :--- | :--- |
| [HongOpenCV](https://github.com/thisNorm/HongOpenCV) | 멀티프레임 글레어 제거와 문서 스캔을 시도한 영상 처리 프로젝트 | `Python` `FastAPI` `OpenCV` `PaddleOCR` |

---

<div align="center">

## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=thisNorm&show_icons=true&theme=transparent&hide_border=true" height="165" alt="Norm's GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=thisNorm&layout=compact&theme=transparent&hide_border=true" height="165" alt="Norm's top languages" />

<br/>

## 📫 Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-thisnorm.dev-20B2F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://thisnorm.dev)
[![Blog](https://img.shields.io/badge/Blog-thisnorm.tistory.com-FF5722?style=for-the-badge&logo=tistory&logoColor=white)](https://thisnorm.tistory.com)
[![Email](https://img.shields.io/badge/Email-kisook2557%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kisook2557@gmail.com)

</div>
