# Story of Dayeon Oh

## Table of Contents
- [**1. Outline**](#outline)
  - [1.1. Profile](#profile)
  - [1.2. Links](#links)
  - [1.3. Education](#education)
  - [1.4. Technical Focus](#technical-focus)
  - [1.5. Experience Snapshot](#experience-snapshot)
  - [1.6. Awards](#awards)
- [**2. Introduction**](#introduction)
  - [2.1. Who I Am](#who-i-am)
  - [2.2. How I Work](#how-i-work)
  - [2.3. Trust](#trust)
  - [2.4. Interests and Fit](#interests-and-fit)
- [**3. Selected Work**](#selected-work)
  - [3.1. Tagging API](#tagging-api)
  - [3.2. Deep Manager](#deep-manager)
  - [3.3. Water Facility Safety System](#water-facility-safety-system)
  - [3.4. License Plate OCR](#license-plate-ocr)
  - [3.5. Dartoo](#dartoo)
  - [3.6. Tomorrow Me](#tomorrow-me)
- [**4. Career and Outputs**](#career-and-outputs)
  - [4.1. Career Summary](#career-summary)
  - [4.2. Outputs Beyond Code](#outputs-beyond-code)
  - [4.3. Study and Knowledge Sharing](#study-and-knowledge-sharing)
- [**5. Links**](#links)

<a id="outline"></a>
## 1. Outline

<a id="profile"></a>
### 1.1. Profile

- Name: 오다연
- Position: AI Backend Engineer
- Focus: AI Serving, Backend Architecture, Performance Optimization, Collaboration Process Improvement

<a id="links"></a>
### 1.2. Links

- GitHub: https://github.com/dayeondev
- Demo: https://tomorrow.me.kr
- Team GitHub:
  - https://github.com/team-1to3
  - https://github.com/team-dartoo
- Presentation:
  - https://youtu.be/vwHFfj6L8e8?si=wANNNZzV4ymlmIRZ
  - https://youtu.be/QPvNc4bxRNg?si=3OMUrqDZlksbcewY

<a id="education"></a>
### 1.3. Education

#### Hanyang University ERICA
- 컴퓨터학부
- `2020.03 ~ 2021.06`, `2024.09 ~ 2027.02 (expected)`

#### Incheon Information Industry High School
- 전산과
- 앱 개발 동아리, 게임 개발 동아리, 인공지능 동아리 운영 경험
- 동아리 회장 및 학생회 경험

<a id="technical-focus"></a>
### 1.4. Technical Focus

#### Backend / AI Serving
- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- RabbitMQ
- Celery
- REST API

#### AI / ML
- PyTorch
- YOLOv5s
- OCR
- LangGraph
- LangGraph SDK
- LLM-based Service Development

#### Infra / DevOps
- Docker
- Docker Compose
- GitHub Actions
- NCP CLI
- Shell Script
- NCP
- AWS
- On-premise
- K3s
- Prometheus
- Grafana
- Loki

<a id="experience-snapshot"></a>
### 1.5. Experience Snapshot

- OGQ | `2021.07 ~ 2025.02`
  - `2023.01 GY Networks 소규모 흡수합병`
- Team Projects | `2025.07 ~ 현재`
- AI 논문 스터디 | `2021.07 ~ 2025.02`

<a id="awards"></a>
### 1.6. Awards

- 2025 한양대학교 SW/ICT/AI 종합학술대회 **우수상**
  - LangGraph를 이용한 개인 맞춤형 청소년 진로상담 서비스 프로젝트
  - 발표 영상: https://www.youtube.com/watch?v=vwHFfj6L8e8
- 2025 한양대학교 SW/ICT/AI 종합학술대회 **최우수상**
  - Dart OpenAPI를 이용한 개인 투자자 대상 금융 비서 시스템 디자인
  - 발표 영상: https://www.youtube.com/watch?v=QPvNc4bxRNg

---

<a id="introduction"></a>
## 2. Introduction

<a id="who-i-am"></a>
### 2.1. Who I Am

저는 AI Backend Engineer로서, 요구사항을 정확히 해석해 운영 가능한 시스템으로 구현하는 데 강점이 있습니다. 특히 AI 서비스에서 자주 발생하는 성능 병목과 협업 비용 문제를 구조적으로 해결해온 경험이 있습니다.

저는 단순히 AI 모델을 API에 연결하는 역할에 머무르지 않고, 시스템이 실제 트래픽과 운영 제약 속에서도 안정적으로 동작하도록 만드는 것까지 제 역할이라고 생각합니다. 그래서 백엔드 개발뿐 아니라, 필요하다면 AI 연구, 인프라 운영, 서비스 기획과 설계, 팀 운영까지 가리지 않고 맡아왔습니다.

<a id="how-i-work"></a>
### 2.2. How I Work

제가 제일 중요하게 생각하는 것은 요구사항을 정확히 이해하는 일입니다. 원하는 게 정확히 무엇인지 파악하지 못하면, 빠르게 만든 결과물도 결국 다시 만들어야 하기 때문입니다. 그래서 상대방이 “이렇게 됐으면 좋겠다”고 말할 때, 그대로 구현하기보다 어떤 점이 불편했는지, 어떤 결과를 기대하는지부터 질문하는 편입니다.

저는 성능 문제를 만났을 때, 단순 튜닝보다 구조를 먼저 봅니다. 로그를 보강해 병목이 어디 있는지 확인하고, 현재 구조가 문제를 만든다면 서비스 구조 자체를 바꾸는 편입니다. 실제로 API 서버와 AI 추론을 분리하거나, 메시지 큐 구조를 조정하거나, 프로세스를 분리하는 방식으로 여러 문제를 해결해왔습니다.

좋은 시스템은 코드만 잘 짠다고 만들어지지 않습니다. 같은 팀이 덜 헤매고 더 정확하게 움직일 수 있어야 합니다. 그래서 문서 없는 진행, 책임이 불분명한 진행을 좋아하지 않습니다. Git submodule 도입, abstract class 정의, 설계 문서 작성, 교통정리 같은 일도 코드 못지않게 중요하게 생각합니다.

<a id="trust"></a>
### 2.3. Trust

이력서를 읽는 사람이 저를 어떻게 기억했으면 좋겠냐는 질문에 대한 제 답은 단순합니다. 믿고 맡길 수 있는 사람. 저는 결국 신뢰가 모든 것을 설명한다고 생각합니다. 말을 하고 지키는 것, 맡은 문제를 끝까지 해결하는 것, 그리고 함께 일하는 사람을 편하게 만드는 것이 중요합니다.

<a id="interests-and-fit"></a>
### 2.4. Interests and Fit

저는 AI를 이용해 사용자의 문제를 해소해주는 서비스를 만드는 일에 관심이 많습니다. 적용할 도메인은 다양할 수 있지만, 특히 금융 자산과 관련된 도메인에 더 큰 관심을 갖고 있습니다. 금융 자산 관리는 모든 사람의 과제이고, 저 역시 스스로 많은 고민을 하고 있는 주제이기 때문입니다. 그래서 팀 프로젝트 주제도 개인 투자자 대상 금융 비서 서비스로 정하게 되었습니다.

근무 형태는 유연하게 열려 있지만, 완전 원격근무보다는 오프라인 접점이 있는 협업 환경을 선호합니다. 밀도 있는 협업과 빠른 문제 해결이 필요한 상황에서는 직접 연결되는 환경이 더 잘 맞는다고 생각합니다.

---

<a id="selected-work"></a>
## 3. Selected Work

<a id="tagging-api"></a>
### 3.1. Tagging API

가장 힘들었지만 잘 해낸 경험을 꼽으라면 Tagging API 구축 프로젝트입니다. 이 프로젝트는 대형 클라우드 스토리지 서비스의 이미지 검색 강화를 위한 AI Tagging API 서버를 구축하는 일이었고, 저는 이 프로젝트에서 백엔드 구조 개선, 배포 자동화, 성능 개선을 중심으로 맡았고, 테스트와 운영 대응, 발주사 커뮤니케이션에도 함께 참여했습니다.

초기 구조에서는 API 서버가 모델 동작까지 함께 처리하고 있었고, 그 결과 초당 API 처리량이 약 600req/s 수준에 머물렀습니다. GPU 사용률도 약 20% 내외로 낮아, 단순한 튜닝만으로는 해결할 수 없는 문제라고 판단했습니다. 당시 병목의 단일 원인을 완전히 분리해 검증할 시간은 없었지만, 로그와 운영 상황을 기준으로 Round Robin 기반 부하분산과 API/추론 결합 구조가 핵심 제약이라고 판단했습니다. 저는 먼저 로그를 보강해 병목을 확인했고, API 서버와 AI 워커를 분리하는 방향으로 구조를 재설계했습니다. 여기에 Celery 기반 태스크 관리, 비동기 이미지 다운로드, RR에서 least-connection 방식으로의 변경 등을 적용했습니다.

테스트와 배포 과정에서는 RabbitMQ의 성능 한계도 별도로 실험했습니다. 더 높은 사양으로 올려도 병목이 해소되지 않았고, 실험상 초당 약 1,400건 부근에서 한계가 나타났습니다. 이에 안정 범위를 약 1,200req/s로 설정하고 worker group과 MQ를 분리하는 구조를 추가로 적용했습니다. 그 결과 초당 API 처리량을 약 600req/s에서 6,250req/s 수준까지 개선해 최종적으로 892% 성능 향상을 달성했습니다. 또한 약 400대 GPU 서버 환경에서 Celery AI worker 배포 자동화 및 실행 구조를 운영했습니다. 이 프로젝트는 제가 AI 백엔드 문제를 모델 자체가 아니라 시스템 구조와 운영 제약까지 포함해 해결한 대표적인 경험입니다.

<a id="deep-manager"></a>
### 3.2. Deep Manager

Deep Manager는 한 개의 장비에서 8종의 자사 AI 모델을 서빙하는 REST API 서버를 개발하고 배포하는 프로젝트였습니다. 백엔드 2명, AI 엔지니어 1명, 프론트엔드 1명이 함께 참여했고, 저는 백엔드 측면에서 API 서버 개발, 추론 구조 분리, 배포 및 모니터링 환경 구성을 담당했습니다.

이 프로젝트에서 중요했던 문제는 기존 구조가 Flask 기반 모놀리식 구조였고, AI팀에서 제공하는 모델마다 요구하는 라이브러리 버전이 달라 충돌이 발생한다는 점이었습니다. 저는 RabbitMQ를 이용해 API 서버와 AI 추론 부분을 분리하는 구조를 선택했고, 각 모델이 개별 프로세스로 동작할 수 있도록 구조를 변경했습니다.

또한 기존 방식대로라면 GPU 서버를 1대 더 추가해야 했지만, 일부 모델을 CPU 추론으로 분리하고 구조를 최적화해 기존 자원 내에서 운영할 수 있도록 만들었습니다. 그 결과 GPU 서버 비용을 50% 절감했고, 데모 서비스의 실제 요청 로그 기준 평균 응답 시간을 500ms 내외로 확보했습니다. 이 프로젝트는 비용, 운영, 아키텍처를 함께 고려해 구조를 설계한 사례였습니다.

<a id="water-facility-safety-system"></a>
### 3.3. Water Facility Safety System

이 프로젝트에서는 백엔드 2명과 AI 연구원 1명이 함께 일했고, 저는 백엔드 서브 역할로 참여했습니다. 주요 업무는 공공 수도시설 15개소를 대상으로 침입, 화재 등 총 8종의 위험상황을 검출하는 AI 모델들이 온프레미스 장비에서 동작할 수 있도록 백엔드 구조를 맞추는 일이었습니다.

이 프로젝트에서 가장 의미 있었던 지점은 AI팀과의 협업 프로세스를 바꾼 경험입니다. 기존에는 AI 관련 파일을 zip으로 전달받은 뒤 변경된 코드를 수작업으로 확인하고 반영해야 했고, 이 과정에서 많은 시간이 소모되었습니다. 이 과정에서 저는 Git submodule과 abstract class 기반 연동 방식을 설계·적용하며, 모델 반영 과정을 더 표준화하는 데 기여했습니다. 이 덕분에 변경점 추적이 쉬워졌고, 관행적으로 반복되던 모델 삽입 과정 자체도 줄일 수 있었습니다.

기술적으로는 Celery task 기반 구조를 적용해 AI 모델들이 안정적으로 동작하도록 만들었고, 그 결과 기술적 이슈로 30%대에 머물던 평균 GPU 사용률을 80% 수준까지 개선했습니다. 협업 측면에서는 모델 업데이트 기간을 30% 단축했습니다. 이 프로젝트는 기술 문제와 협업 문제를 함께 풀어낸 경험으로 기억하고 있습니다.

<a id="license-plate-ocr"></a>
### 3.4. License Plate OCR

번호판 OCR 프로젝트는 원래 자동차 번호판 데이터를 레이블링하는 업무에서 출발했습니다. 하지만 저는 단순히 레이블링 작업만 반복하는 것보다, 이 문제를 근본적으로 해결할 수 있는 방식이 무엇인지 고민했습니다. 그래서 주간 회의에서 OCR 프로그램과 번호판 인식 방식을 따로 조사하고, 이 문제를 더 나은 방식으로 해결할 수 있는 가능성을 제안했습니다.

이후 저는 번호판 인식 및 OCR 관련 구현을 주도했고, AI 연구원분들의 조언을 반영해 내부 테스트셋 기준 mAP 95.3%를 달성했습니다. 이 경험은 단순히 주어진 작업을 수행하는 데 그치지 않고, 실제 문제를 해결하는 방향으로 역할을 확장한 초기 경험이었습니다.

<a id="dartoo"></a>
### 3.5. Dartoo

Dartoo는 6명이 함께 진행한 팀 프로젝트로, 개인 투자자를 위한 금융 공시 요약 서비스를 만드는 프로젝트였습니다. 이 프로젝트에서는 팀 리드이자 AI 백엔드 담당으로서, 설계 문서 작성과 요약 worker 구현을 중심으로 기여했습니다.

이 프로젝트에서 저는 소프트웨어 기획과 설계 문서 작성, 공시 자료를 AI로 요약하는 Celery worker 개발을 맡았습니다. 이 프로젝트는 제가 특히 관심 있는 금융 자산 도메인과 맞닿아 있었고, 개인 투자자가 정보 비대칭을 줄일 수 있도록 돕는다는 점에서 의미가 컸습니다.

<a id="tomorrow-me"></a>
### 3.6. Tomorrow Me

Tomorrow Me는 4명이 함께 진행한 팀 프로젝트로, LangGraph와 Aegra를 이용한 청소년 진로상담 서비스입니다. 저는 이 프로젝트에서 기획과 설계를 주도했고, LangGraph 기반 진로상담 Agent 개발과 compose 배포를 맡았습니다.

초기에는 LangGraph SDK 없이 LLM을 독립적으로 호출하는 방식이었는데, 이 구조에서는 사용자 정보를 안정적으로 유지하기 어렵고 대화 흐름의 자유도도 낮았습니다. 기존 방식은 강점 추출 2회, 관심분야 분석 2회처럼 단계가 고정되어 있어 사용자 특성을 충분히 수집하기 어려운 한계도 있었습니다. 이후 LangGraph 기반 state 관리 구조를 도입하면서 사용자 정보를 더 자연스럽게 축적할 수 있게 되었고, 상담 흐름의 유연성과 유지보수성도 함께 개선되었습니다. 필요한 정보가 충분히 수집될 때까지 자연스럽게 대화를 이어갈 수 있게 된 점이 가장 큰 차이였습니다. Agent 배포 시에는 Aegra를 이용해 외부 종속성 없이 직접 배포 가능한 구조를 만들었습니다.

Demo: https://tomorrow.me.kr

---

<a id="career-and-outputs"></a>
## 4. Career and Outputs

<a id="career-summary"></a>
### 4.1. Career Summary

저는 초등학교 때부터 컴퓨터로 무언가를 만드는 일에 관심이 많았습니다. 방과 후 컴퓨터 수업을 듣고 각종 자격증을 따면서 자연스럽게 컴퓨터로 일하는 삶을 떠올리게 되었고, 중학생 때는 정보처리기능사와 정보 올림피아드를 준비하며 프로그래밍을 직업으로 삼아야겠다고 마음먹었습니다.

고등학교에서는 앱 개발, 게임 개발, 인공지능 관련 동아리를 운영했고, 학생회와 부학생회장 경험도 하며 사람들과 함께 무언가를 만들고 운영하는 경험을 쌓았습니다. 대학교에서는 팀 프로젝트를 통해 기획 문서, 설계 문서, 유즈케이스, 아키텍처 드라이버 같은 문서를 직접 작성하며 구조적으로 소프트웨어를 만드는 훈련을 해왔습니다.

실무에서는 2021년부터 OGQ에서 AI 백엔드 개발을 맡아왔습니다. 2023년 1월에는 GY Networks가 소규모 흡수합병되었고, 저는 같은 조직 맥락 안에서 AI 서비스 백엔드, 분산 처리, 성능 최적화, 운영 자동화, 협업 프로세스 개선으로 역할을 확장해왔습니다.

<a id="outputs-beyond-code"></a>
### 4.2. Outputs Beyond Code

학교 팀 프로젝트에서는 Notion을 기반으로 기획 문서, 설계 문서, 유즈케이스, 아키텍처 드라이버 등을 정리해왔습니다. 저는 문서를 남기는 것이 단지 정리 습관이 아니라, 함께 일하는 사람들의 시간을 아끼는 구조라고 생각합니다.

<a id="study-and-knowledge-sharing"></a>
### 4.3. Study and Knowledge Sharing

실무에서는 2021년 7월부터 2025년 2월까지 사내 AI 논문 스터디에 참여했고, 컴퓨터 비전 논문 40~50편 이상을 분석하고 발표했습니다. 이는 단순 학습을 넘어 실무 적용과 팀 내 커뮤니케이션 역량을 함께 키운 경험이었습니다.

---

## 5. Links

- GitHub: https://github.com/dayeondev
- Demo: https://tomorrow.me.kr
- Team GitHub:
  - https://github.com/team-1to3
  - https://github.com/team-dartoo
- Presentation:
  - https://youtu.be/vwHFfj6L8e8?si=wANNNZzV4ymlmIRZ
  - https://youtu.be/QPvNc4bxRNg?si=3OMUrqDZlksbcewY
