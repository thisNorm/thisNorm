<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=230&color=gradient&text=Norm%20%7C%20Backend%20Engineer&fontAlign=50&animation=fadeIn&fontColor=ffffff&fontSize=50&desc=Edge%20Systems%20%C2%B7%20Data%20Pipelines%20%C2%B7%20AI-enabled%20Workflows&descAlign=50&descSize=18)

### Code with Rhythm, Ship with Impact! 🎶

AI를 활용해 개발 생산성을 높이고, 복잡한 비즈니스 로직을 안정적인 서비스 파이프라인으로 구현하는  
**백엔드 엔지니어 황규범(Norm)** 입니다.

스마트팜 엣지 서버부터 폐쇄망 AI 관제, 비동기 데이터 파이프라인, 온디바이스 AI까지  
**현실의 제약 속에서도 안정적으로 동작하는 시스템**을 만드는 데 집중합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-thisnorm.dev-20B2F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://thisnorm.dev)
[![Tech Blog](https://img.shields.io/badge/Tech_Blog-규범이의_코딩_맛집-FF5722?style=for-the-badge&logo=tistory&logoColor=white)](https://thisnorm.tistory.com)
[![Email](https://img.shields.io/badge/Email-kisook2557%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kisook2557@gmail.com)

</div>

---

## 👋 About Me

현재 **인포벨리코리아 백엔드 엔지니어**로 스마트팜 엣지 서버와 현장 데이터 파이프라인을 개발하고 있습니다.

- **Edge & IoT Backend** — 현장 네트워크·PC·디바이스 세팅부터 서버 연동과 데이터 수집까지 엣지 운영 전 구간을 다룹니다.
- **Reliable Data Pipeline** — Redis Queue, DLQ, 프록시 모듈을 활용해 통신 장애와 일시적인 서버 중단에도 데이터를 보존합니다.
- **Constraint-driven Architecture** — 폐쇄망, Android OS 보안 제약, 대용량 이벤트 병목처럼 시스템 기저의 문제를 아키텍처 재설계로 해결합니다.
- **AI-enabled Engineering** — 로컬 LLM과 멀티 에이전트 워크플로우를 개발·검증·콘텐츠 운영 과정에 적용합니다.

> 새로운 기술을 나열하는 것보다, 실제 운영 환경에서 발생한 문제를 추적하고 가장 작은 올바른 구조로 해결하는 것을 중요하게 생각합니다.

---

## 💼 Professional Experience

### 주식회사 인포벨리코리아 · Backend Engineer
`2026.06 — Present` · 스마트팜 엣지 서버 / 현장 인프라

- 스마트팜 클라우드 서비스의 **엣지 서버 및 데이터 파이프라인 아키텍처** 설계·개발
- 소리 수집기, 비콘 등 다중 하위 모듈의 유기적 동작을 위한 **마이크로서비스 오케스트레이션** 및 모듈 단위 고립 테스트 체계 도입
- 프록시 모듈과 Redis를 활용한 **엣지–클라우드 데이터 유실 방지 구조** 구축
- 현장 네트워크 구성, 서버·PC 세팅, 디바이스 통신 연동과 장애 진단 수행

`Node.js` `JavaScript` `Redis` `SQLite` `Linux` `Docker` `Networking` `IoT`

### 한국전자통신연구원(ETRI) 자율형 IoT 연구실 · Research Intern
`2026.01 — 2026.02` · AI 기반 폐쇄망 통합 관제

- YOLOv8 기반 CCTV와 이동형 로봇을 통합한 **실시간 관제 시스템 백엔드** 설계
- Redis Queue와 DLQ를 도입해 대용량 이벤트의 **비동기 처리 및 장애 복구 구조** 구축
- 객체 단위 이벤트 그룹화와 배치 저장으로 데이터베이스 Write 부하 감소
- 폐쇄망 내 카메라 스트리밍, 객체 탐지, 원격 제어, 이벤트 저장 파이프라인 통합

`Python` `FastAPI` `.NET 8` `Redis` `SQLite` `WebSocket` `YOLOv8` `OpenCV`

---

## 🚀 Featured Projects

### 1. DeepVoice Shield · 실시간 딥보이스 탐지 및 보이스피싱 예방

클라우드 추론의 지연과 모바일 OS 제약을 해결하기 위해 **온디바이스 AI 중심으로 아키텍처를 전환**한 풀스택 프로젝트입니다.

- TFLite 기반 모델 최적화로 모델 용량을 약 **91% 경량화**
- Android의 통화 음성 접근 제약을 우회하기 위한 **자체 VoIP·P2P 통신 파이프라인** 구축
- 모바일 실시간 탐지, 백엔드 API, 웹 체험 페이지, AI 알고리즘을 독립 모듈로 구성
- 디지털 바이오헬스 경진대회 대상, 충청권 ICT 이노베이션스퀘어 대상 등 수상

| Component | Repository | Main Tech |
| :--- | :--- | :--- |
| Backend | [deepfake_detection_service_backend](https://github.com/thisNorm/deepfake_detection_service_backend) | `NestJS` `Socket.io` `AWS EC2/S3` |
| Mobile | [deepfake_detection_service_application](https://github.com/thisNorm/deepfake_detection_service_application) | `React Native` `Android` `TFLite` |
| Algorithm | [deepfake_detection_service_algorithm](https://github.com/thisNorm/deepfake_detection_service_algorithm) | `PyTorch` `ONNX` `TFLite` |
| Frontend | [deepfake_detection_service_frontend](https://github.com/thisNorm/deepfake_detection_service_frontend) | `React` `Vite` |

### 2. [content-agent](https://github.com/thisNorm/content-agent) · 멀티 에이전트 콘텐츠 운영 자동화

Notion에 초안을 작성하면 채널별 특성에 맞게 콘텐츠를 가공하고 배포하는 **다채널 운영 자동화 파이프라인**입니다.

- 블로그, Threads, X 등 채널별 문체와 길이에 맞춘 콘텐츠 자동 변환
- 텍스트 생성, 검수, 썸네일 생성, 배포 단계를 역할별 에이전트로 분리
- 실패 단계 재처리와 운영 상태 추적을 고려한 워크플로우 설계

`TypeScript` `Next.js` `Notion API` `Multi-Agent Workflow` `Automation`

### 3. [Air-gapped DevOps](https://github.com/thisNorm/Air-gapped_DevOps) · 폐쇄망 AI 배포 자동화

외부망이 차단된 환경에서도 안전하게 개발·검증·배포할 수 있도록 구성한 **로컬 AI 기반 DevOps 아키텍처**입니다.

- GitLab 기반 로컬 CI/CD 파이프라인 설계
- 로컬 LLM을 활용한 코드 분석 및 배포 자동화 구조
- 프롬프트 주입과 비정상 코드 실행을 차단하기 위한 Docker Sandbox 검증 환경 설계

`GitLab CI/CD` `Docker` `Local LLM` `Linux` `Security Validation`

### 4. [HongOpenCV](https://github.com/thisNorm/HongOpenCV) · 멀티프레임 글레어 제거 문서 스캐너

여러 프레임의 정보를 결합해 문서의 반사광을 제거하고 가독성을 복원하는 영상 처리 프로젝트입니다.

- Multi-frame Merge, Specular Masking, Inpainting, Perspective Warping 적용
- 무거운 영상 처리 작업을 비동기 파이프라인으로 분리해 백엔드 병목 방지
- OpenCV Zoo 기반 영상분석 실무 프로젝트 최우수상 수상

`Python` `FastAPI` `OpenCV` `PaddleOCR` `React`

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
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Data, Infra & Communication**

![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)

**AI, Vision & Workflow**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![On-device AI](https://img.shields.io/badge/On--device_AI-6A5ACD?style=flat-square)
![Local LLM](https://img.shields.io/badge/Local_LLM-222222?style=flat-square)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Workflow-74AA9C?style=flat-square)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)

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

## 📂 More Projects

| Project | Description | Tech |
| :--- | :--- | :--- |
| [content-agent-landing](https://github.com/thisNorm/content-agent-landing) | 콘텐츠 자동화 시스템 B2B 소개 사이트 | `Next.js` `TypeScript` |
| [My Portfolio](https://github.com/thisNorm/portfolio) | 개인 포트폴리오 웹사이트 | `React` `Web` |
| [WeGive](https://github.com/thisNorm/WeGive) | 재능 나눔 서비스와 단계형 거래 상태 관리 | `Java` `Web` |
| [CodingTest](https://github.com/thisNorm/codingtest) | 알고리즘 문제 풀이 아카이브 | `Algorithm` |

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
