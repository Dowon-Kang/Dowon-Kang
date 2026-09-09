<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:38BDF8&height=220&section=header&text=Dowon%20Kang&fontSize=52&fontColor=FFFFFF&fontAlignY=38&animation=fadeIn" alt="Dowon Kang header" />

### Signals · AI Systems · Service Architecture

영상·음성·EEG와 같은 **신호 데이터**를 이해하고,  
AI 기능을 **백엔드와 클라우드 서비스**로 연결하는 과정을 공부하고 있습니다.

`AI/Signal` → `Inference & Evaluation` → `Backend/API` → `Cloud` → `Service`

<!-- 실제 주소를 입력한 뒤 아래 주석을 해제하세요.
<p>
  <a href="YOUR_NOTION_URL"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
-->

</div>

## About Me

안녕하세요. **AI Solution Architect**를 목표로 성장하고 있는 강도원입니다.

AI 모델을 호출하는 것에서 끝내지 않고, 사용자의 문제를 정의한 뒤 모델 평가, API, 데이터베이스, 배포와 운영까지 하나의 시스템으로 설계하는 데 관심이 있습니다. 현재는 백엔드 개발과 AI 기능 연동 경험을 기반으로 소프트웨어 아키텍처와 신호 처리 역량을 넓혀 가고 있습니다.

- AI 기능을 REST API·인증·데이터베이스와 연결한 서비스 개발
- 정량 평가를 통한 모델 응답 품질 분석 및 개선
- IoT 중앙 서버와 모바일–하드웨어 연동 구조 설계
- 팀·스터디 운영과 Python 멘토링

## Selected Projects

### Context Bridge — AI Communication Service

문맥 정보를 활용해 대화를 돕는 AI 커뮤니케이션 서비스입니다.

- **담당:** Node.js·Express 기반 REST API, Supabase Auth·PostgreSQL 연동, Gemini API 통합
- **검증:** held-out 40문항·340쌍 기준 Precision 88.7%, Recall 79.2%, F1 83.7%
- **배운 점:** 모델 출력 품질은 프롬프트뿐 아니라 데이터 구조, 평가 기준, 예외 처리까지 함께 설계해야 한다는 점
- **Tech:** `React` `TypeScript` `Node.js` `Express` `Supabase` `PostgreSQL` `Gemini API`

### ABC25 — oneM2M IoT Central Server

Mobius를 활용해 IoT 디바이스의 인식 데이터를 수집·저장하는 중앙 서버 구조를 구현했습니다.

- **담당:** Mobius 서버 구축, `FacialEmo AE` 구성, emotion·object 컨테이너 설계, REST 기반 데이터 연동
- **배운 점:** 디바이스–서버 간 데이터 모델과 인터페이스 계약이 전체 연동의 기준이 된다는 점
- **Tech:** `oneM2M` `Mobius` `REST API` `IoT`

### Koetodoke — Korea–Japan Inclusive AI Ideathon

독거 고령자의 장보기 어려움을 해결하기 위해 음성·이미지·문자 신호를 하나의 사용자 흐름으로 연결한 서비스입니다.

- **담당:** 문제 정의, 음성 주문 UX, OCR·이미지 인식 기능, 재주문 및 가족 공동 케어 흐름 설계
- **협업:** 한국·일본 학생 간 서비스 기획 및 발표
- **Tech:** `Inclusive AI` `Voice UI` `OCR` `VLM` `Service Design`
- **Related:** [2026 Korea–Japan Bridge Ideathon](https://www.kyosu.net/news/articleView.html?idxno=209710)

### Vibration Control Mobile App `In Progress`

사용자 데이터와 외부 API를 바탕으로 진동 강도를 계산하고 하드웨어 장치에 전달하는 Flutter 앱을 개발하고 있습니다.

- **담당:** 모바일 UI/UX, 외부 API 연동, 계산 로직과 장치 전송 인터페이스 설계
- **현재 과제:** 센서·장치 API 연동, 불안정한 네트워크 처리, 계산 근거 검증
- **Tech:** `Flutter` `Dart` `REST API` `Hardware Integration`

### EEG-based AI Research `In Progress`

BrainAccess 4채널 EEG를 활용한 측정·분석 환경을 준비하고 있습니다.

- **현재 작업:** 실험 질문과 프로토콜 설계, 측정 환경 구성, 전처리·분석 파이프라인 학습
- **관심:** 시간에 따라 변화하는 생체 신호에서 의미 있는 패턴을 추정하고 서비스 문제와 연결하는 방법
- **Tech:** `Python` `EEG` `Signal Processing` `Experimental Design`

### AI Model Experiment & Evaluation

교내 NVIDIA A100 GPU 서버에서 Linux·Remote SSH 환경을 구성하고 AI 모델을 실행·평가했습니다.

- **담당:** 실행 환경 구성, 모델 테스트, 결과 비교 및 성능 분석
- **Tech:** `Python` `Linux` `NVIDIA A100` `Remote SSH`

## Experience at a Glance

| Area | Experience |
| --- | --- |
| **AI integration** | Gemini API 연동, 모델 응답 평가, OCR·VLM 기능 설계 |
| **Backend & data** | REST API, Node.js·Express, Supabase Auth, PostgreSQL |
| **Systems** | oneM2M·Mobius 중앙 서버, 모바일–하드웨어 연동 구조 |
| **Research** | EEG 실험 설계 및 신호 처리 학습, A100 모델 실험 |
| **Collaboration** | 랩·스터디 운영, Python 멘토링, 한·일 팀 프로젝트 |

## Tech

### Used in Projects

`Python` `TypeScript` `JavaScript` `Node.js` `Express` `React`  
`Supabase` `PostgreSQL` `Flutter` `Dart` `Git` `GitHub` `Linux`  
`REST API` `Gemini API` `oneM2M` `Mobius`

### Fundamentals

`C` `C++` `Java` `Data Structures` `Algorithms` `Object-Oriented Programming`

### Currently Learning

| Focus | Topics |
| --- | --- |
| **AI systems** | `VLM` `RAG` `AI Agent` `Model Evaluation` |
| **Software architecture** | `Requirements` `UML` `System Design` `Design Patterns` `API Design` |
| **Cloud & operations** | `AWS` `Docker` `CI/CD` `Monitoring` |
| **Signals & research** | `EEG` `Signal Processing` `Experimental Design` |

## Leadership & Community

| Organization | Role | What I Do |
| --- | --- | --- |
| **AISC Lab** | Lab Leader | 랩 운영 및 프로젝트·스터디 활동 지원 |
| **AISC Programming Study** | Study Leader | C 프로그래밍 스터디 운영 |
| **AISC Mentoring** | Mentor | Python 학습 멘토링 |
| **C++ Algorithm Study** | Member | 알고리즘과 문제 해결 학습 |

## Education & Activities

- **Hanshin University** — AISW, Undergraduate
- **2026 ABC Camp / ABC DO Hackathon** — AI service development · [Event article](https://www.christiandaily.co.kr/news/163278)
- **2026 Korea–Japan Bridge Ideathon** — Inclusive AI service planning · [Event article](https://www.kyosu.net/news/articleView.html?idxno=209710)
- **Digital Competition** — AI model experiment and evaluation on NVIDIA A100

## Problem-Solving Practice

<div align="center">

<img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=kd2713st" alt="Solved.ac profile for kd2713st" />

</div>

## Next Step

현재의 목표는 특정 직함을 먼저 내세우는 것이 아니라, 아래 질문에 답할 수 있는 프로젝트를 쌓는 것입니다.

> 어떤 문제를 해결하는가?  
> 모델의 결과가 실제로 유효한가?  
> 컴포넌트는 어떤 계약으로 연결되는가?  
> 서비스는 어떻게 배포·관찰·개선되는가?

요구사항, 아키텍처, AI 평가, 보안, 배포와 모니터링을 함께 다루며 **AI를 실제 환경에서 안정적으로 사용할 수 있는 시스템**을 설계하는 사람으로 성장하고 있습니다.

<div align="center">

<sub>From signals to reliable AI services.</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:38BDF8&height=110&section=footer" alt="Footer" />

</div>
