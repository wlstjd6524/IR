# Information Retrieval - Scientific Knowledge Question Answering
목적 : 질문과 이전 대화 히스토리를 보고 참고할 문서를 검색엔진에서 추출 후 이를 활용하여 질문에 적합한 대답을 생성하는 태스크 구현

## 👨‍👧‍👦 Team 
<table align="center">
  <!-- 상단 팀원 이름 Table-->
  <tr>
    <th align="center">👑 이진성</th>
    <th align="center">🙍 고아연</th>
    <th align="center">🙍‍♂ 김재현</th>
    <th align="center">🙍‍♂ 박성재</th>
    <th align="center">🙍‍♂ 배준서</th>
    <th align="center">🙍 윤소정</th>
  </tr>
  
  <!-- 팀원 이미지 Table-->
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a9befe05-0cb9-4e0c-ba1f-43b4275ce55e" width="130">    <!--이진성-->
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/35c220cf-9b00-4e9a-a3e9-0e2e3e2318b7" width="120">    <!--고아연-->
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/89342c37-c1f9-4fcf-9ef9-a9fc032a807f" width="125">    <!--김재현-->
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/21d5ac6e-c2c9-47a8-867a-7cb362f05973" width="120">    <!--박성재-->
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/e10fba61-2421-4bca-b470-506f854fa909" width="115">    <!--배준서-->
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/10778e56-ea3c-4e64-8204-3ab5a5d2df36" width="115">    <!--윤소정-->
    </td>
  </tr>

  <!-- 팀원 역할 Table-->
  <tr>
    <!--이진성-->
    <td align="center">
      EDA <br>
      RAG PipeLine
    </td>
    <!--고아연-->
    <td align="center">
      EDA <br>
      RAG PipeLine
    </td>
    <!--김재현-->
    <td align="center">
      EDA <br>
      RAG PipeLine
    </td>
    <!--박성재-->
    <td align="center">
      EDA <br>
      RAG PipeLine
    </td>
    <!--배준서-->
    <td align="center">
      EDA <br>
      RAG PipeLine
    </td>
    <!--윤소정-->
    <td align="center">
      EDA <br>
      RAG PipeLine
    </td>
  </tr>

  <tr>
    <td align="center">
      <a href="https://github.com/wlstjd6524"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>        <!--이진성-->
    </td>
    <td align="center">
      <a href="https://github.com/ayoun88"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>           <!--고아연-->
    </td>
    <td align="center">
      <a href="https://github.com/KJH-0596"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>          <!--김재현-->
    </td>
    <td align="center">
      <a href="https://github.com/sungjae3911-arch"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>  <!--박성재-->
    </td>
    <td align="center">
      <a href="https://github.com/jun-01111"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>         <!--배준서-->
    </td>
    <td align="center">
      <a href="https://github.com/Lucia128"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>          <!--윤소정-->
    </td>
  </tr>

</table>

## 📺 Presentation
[발표자료](https://github.com/user-attachments/files/27000298/IR1._.pptx)


## 📂 ReadME Index 
[🎯 Project Overview (프로젝트 개요 및 목표)](#project-overview) <br>

[📊 Experimental Setup & Data Pipeline (실험 환경 및 데이터 파이프라인)](#experimental-setup) <br>

[🧪 Key Experiments & Methodology (핵심 실험 및 방법론)](#key-experiments) <br>

[🚀 Results & Optimization (결과 분석 및 최적화 과정)](#results-optimization) <br>

[👥 Team Leadership & Management (팀 리더십 및 협업)](#team-leadership) <br>

[📈 Retrospective & Future Work (회고 및 향후계획)](#retrospective)


<a id="project-overview"></a>

## 🎯 Project Overview
### 프로젝트 배경


### 🔧 Tech Stack
| Category | Tech Stack |
| :--- | :--- |
| **Framework & Orchestration** | LangChain, LangGraph |
| **LLM Model** | Upstage Solar-Pro |
| **Database & Storage** | ChromaDB (Vector), SQLite (RDB), AWS S3 |
| **Data Pipeline & NLP**| BM25 (Sparse Retrieval), DocTR (OCR), KoNLPy (형태소 분석) |
| **Tools & API** | Tavily API (Web Search), OpenDartReader |
| **Monitoring & UI** | LangSmith (Tracing), Gradio (Prototype UI) |

<a id="experimental-setup"></a>

## 📊 Experimental Setup & Data Pipeline


### 🏆 Key Contributions (개인 기여 파이프라인)
| **Category** | Details |
| :--- | :--- |
| **Role** | Technical Lead(팀 일정 조율 및 협업 프로세스 주도, PR/Merge 관리) |
| **Core Pipelines** | Senantic Router, Custom LLM Judge |
| **Custom Tools** | Carbbon Emission Calculator(탄소 배출 계산기), Security Compliance Checklist(정보 보호 인증 규정 분석) |
| **Data Engineering** | CustomTool 에 필요한 실무 데이터(정형/비정형) 수집 및 LLM 이 학습을 진행할 때 효율을 높이기 위한 표준 컬럼 매핑 전처리 |


<a id="key-experiments"></a>

## 🧪 Key Experiments & Methodology


<a id="results-optimization"></a>

## 🚀 Results & Optimization
### 1. 전문 도메인(ESG) 데이터 수집 및 데이터 스키마 설계의 한계 극복
#### 문제 정의
ESG는 글로벌 공시 규제와 법률적 전문성이 요구되는 생소한 도메인으로, 신뢰성 있는 학습/참조 데이터를 확보하는데 어려움이 있었습니다. 특히 글로벌 대응을 위해 해외 전문 자료를 파싱해야 하는 과정에서 데이토 소스의 불일치 문제가 발생했습니다.

#### 원인 분석
단순 검색으로는 실무자가 필요로 하는 정밀한 계산 계수와 법적 근거를 추출할 수 없었고, 도메인 지식의 깊이가 부족하여 초기 데이터 전처리 방향 설정에 혼선이 있었습니다.

#### 해결 방안
SK,LG 등 선도 기업의 ESG 지속가능경영보고서를 정밀 분석하여 실무 핵심지표를 도출하고 기존 ESG 타겟 솔루션들의 로직을 분석하고 실제로 해당 도메인을 타겟하는 여러 프로그램들이 존재하여 그 프로그램들의 방향성을 벤치마킹하여 에이전트가 필요로 하는 데이터 구조 설계를 진행하였습니다. 이를 통해 정형 데이터(계수) 와 비정형 데이터 (규제 가이드라인)의 표준을 정의하고 전처리 효율을 개선했습니다. 

#### 인사이트
<b>도메인에 대한 깊은 이해가 AI 파이프라인의 논리적 구조와, 더 양질의 데이터를 만들어 낼 수 있는 방향성 정의 그리고 최종 성능을 결정한다</b>는 원칙을 얻게되었습니다.

---

### 2. 유지보수성을 고려한 모듈 독립성 확보 및 연쇄작용 구현
#### 문제 정의
시스템의 유지보수성을 위해 각 CustomTool 은 독립적이어야 하지만, 실제 답변 생성을 위해서는 여러 도구가 유기적으로 연쇄 반응을 일으켜야 하는 설계상의 모순에 직면했습니다.

#### 원인 분석
도구 내부에 다른 도구에 대한 의존성이 직접 코딩될 경우, 하나의 모듈 수정이 전체 시스템의 오류로 전파되는 <b>강한 결합</b> 문제가 발생할 위험이 있었습니다. 또한 실제로 몇 개의 Tool 에서는 다른 Tool 을 하드코딩 하는 방식으로 Tool 구성이 이루어져 있어서 실제로 의존성 문제가 발생하였습니다.

#### 해결방안
각 Tool 은 오직 자신의 고유 기능에만 집중하도록 원자적 단위로 설계했습니다. <br>
이에 따라 도구 간의 연결 로직을 코드 레벨이 아닌, <b>LangGraph의 상태 전이와 LLM의 프롬프트 제어</b> 로 권한을 부여했습니다. 에이전트가 현재 상태를 판단하여 다음 도구를 호출하도록 유도하는 '프롬프트 가드레일' 을 구축하여 시스템의 유연성을 확보했습니다.

#### 인사이트
<b>복잡한 파이프라인일수록 로직은 원자적으로 분리하되, 흐름 제어는 오케스트레이터에 맡기는 것이 유지보수성을 극대화하는 길</b> 임을 확인했습니다.

---

### 3. 모듈 간 의존성 관리 및 인터페이스 규격화를 통한 병렬 개발 최적화
#### 문제 정의
데이터 적재 방식의 변경이 하위 Custom Tool의 호출 로직과 충돌하며 시스템 전체의 불안정성을 초래하고, 이로 인해 개발 생산성이 저하되는 병목 현상이 발생했습니다.

#### 원인 분석
프로젝트 초기, 데이터 파이프라인과 Custom Tool 파이프라인 간의 "입출력 데이터 규격" 이 엄격하게 정의되지 않은 채 개발이 진행되어, 파이프라인 통합 시 잦은 수정과 불필요한 회의가 반복되었습니다.

#### 해결 방안
각 모듈이 주고 받는 데이터 형식을 JSON 으로 선제 정의하여, 데이터 파이프라인의 변경이 Tool 로직에 미치는 영향을 최소화 하고, 팀 리더로서 각 파이프라인의 의존 관계를 재설계하고, <b>독립적 단위 테스트</b> 환경을 구축하여 팀원들이 서로의 진행 상황에 구애받지 않고 병렬로 기능을 고도화할 수 있도록 조율했습니다.

#### 인사이트
<b>협업의 효율은 단순한 대화가 아닌, 명확한 기술 규격과 문서화된 인터페이스에서 나온다</b> 는 점을 실감했습니다.

---

### 4. 에이전트 루프 중복 실행 방지 및 3분 이상의 응답 지연 개선
#### 문제 정의
특정 도구 호출 시 에이전트가 동일한 데이터 파싱 과정을 반복적으로 수행하여 응답 시간이 3분 이상 소요되거나, 타임아웃(Timeout) 에러가 발생하는 등 서비스 불가능 수준의 성능 저하가 확인되었습니다.

#### 원인 분석
프롬프트 내 제어 지시문이 모호하여 LLM이 출력 결과에 확신을 갖지 못하고 보수적으로 작동하거나, 데이터 구조를 오인하여 불필요한 연산을 재수행하는 것이 원인이었습니다.

#### 해결 방안
페르소나 부여 규칙을 엄격히 준수하고, "절대 중복 파싱을 하지 말 것" 과 같은 <b>부정 지시어</b> 와 <b>Few-shot</b> 예시를 보강하여 에이전트의 판단 경로를 단순화했습니다. <br>
또한 `Pydantic` 을 활용하여 데이터 추출 형식을 강제함으로써 LLM 의 해석 오류를 사전에 차단하고, 파이프라인의 전체 실행 시간을 획기적으로 단축하여 타임아웃 문제를 해결했습니다.

#### 인사이트
<b>코드 로직만큼이나 정교한 프롬프트 제어가 에이전트 기반 시스템의 실제 성능과 비용 효율성을 결정짓는 핵심 엔지니어링 요소임</b>을 깨달았습니다.

<a id="team-leadership"></a>

## 👥 Team Leadership & Management
프로젝트 팀장으로서 단순한 일정 관리를 넘어, 기술적 병목 현상을 제거하고 개발 효율을 극대화하기 위한 `협업시스템` 을 설계했습니다.

### GitHub 기반 코드 버전 관리
GitHub 작업 레포를 만들어 Contributors 로 팀원을 초대하고, 레포에 존재하는 Push, Merge 규칙을 "1명 이상의 작업자가 승인 시 Merge" 라는 항목을 부여하여 모든 팀원이 코드를 실시간으로 관리할 수 있게 레포 관리를 주도했습니다. <br>
[GitHub 작업레포](https://github.com/wlstjd6524/LangchainRag_01)

### 팀원간 정보 격차 관리 및 함께 성장하는 프로젝트 방향성 수립
Notion 을 활용해 도메인 지식을 관리하고, Slack 을 통해 팀원에게 프로젝트간 이행해야 할 규칙들을 명시함으로써 팀원 간의 정보 격차를 해소하고 함께 성장하는 프로젝트 목표를 수립하고자 노력하였습니다. <br>
또한 텍스트로만 주고받는 정보는 인지에 한계가 있다고 판단하여 프로젝트 진행상황 및 일정을 고려하여 Zoom 으로 실시간으로 공유하고자 하였습니다. <br>
[Notion](https://www.notion.so/ESG-Tool-23d6325e11938098aa97e22ed903393b)

<a id="retrospective"></a>

## 📈 Retrospective & Future Work
### 📌 회고
이번 프로젝트를 통해서 전 프로젝트를 통해 배웠던 RAG 파이프라인을 어떻게하면 더 잘 활용할 수 있는지, 또한 랭체인에 대한 전반적인 파이프라인을 이해할 수 있는 좋은 프로젝트 였던 것 같습니다. <br>
수행하면서 어려웠던 점은 바로 <b>도메인에 대한 이해</b> 와 <b>파이프라인 간의 독립성 확보</b> 그리고 <b>독립성이 확보된다 하지만 그런 부분들이 연쇄적으로 작용해야 한다는 점</b> 들이 어려웠던 점으로 작용했던 것 같습니다. <br>

보통 상품화를 할 수 있는 프로그램을 만드는 프로젝트에서 항상 고민했던 점은 "어떻게 하면 유지보수를 조금 더 쉽게 가져갈 수 있을까?" 라는 점을 기반으로 파이프라인을 구성하려고 노력하는데, 이번 프로젝트에서 "Tool 들은 그들만의 기능을 가질 수 있게 독립성을 확보해야 하지만, 다른 Tool 들과 연쇄적으로 작용 할 수 있어야 한다" 라는 접근성이 제가 항상 생각하는 "유지보수 장점에 용이" 라는 고민을 조금 더 어렵게 하지 않았나 라는 생각이 들었습니다. <br>

또한 각 Tool 들 간의 연쇄작용이 중요하다 보니 독단적으로 하나의 파이프라인을 맡아도 다른 파이프라인을 맡는 팀원들과 꾸준히 커뮤니케이션을 진행해야 한다는 점도 어려웠던 점으로 작용했던 것 같습니다. <br>
이런 작은 프로젝트에서 마저도 많은 회의를 요구했는데 실무에서는 얼마나 많은 팀회의를 걸칠지 생각해 볼 수 있는 좋은 기회 였던 것 같습니다. <br>

마지막으로 항상 생각했던 "데이터의 품질" 에 대한 중요성을 넘어서 이런 좋은 데이터의 품질의 기반은 "도메인 지식을 깊게 이해해야 한다는 점" 을 인지했고, 만만하게만 생각했던 프롬프트 와 페르소나 부여가 전체적인 파이프라인을 장악할 수 있을 정도로 영향력이 크다 라는 점도 새롭게 알고 인지하게 되었습니다.

### 📗 향후계획
제가 맡은 `LLM Judge` Tool 을 현재 프로젝트에서는 백엔드에서 개발자가 시스템 성능이 어떻게 나오는지 지표로 판단하고 서비스 품질을 향상시키기 위한 인증서로 삼기위해서 수동으로 돌려야 하는 로직을 배경으로 두고 구현을 했습니다. <br>
향후 프로젝트 고도화를 진행하게 된다면 이런 로직이 LLMOps 기반 으로 자동화 시킬 수 있는 WorkFlow 로 개선해보고 싶고, 또한 토큰 사용량이나 사용자에게 답변을 던지는 시간에 영향이 많이 가지 않는다면 LLM 이 사용자에게 답변을 던지기 전에 자체적으로 제가 구현한 `LLM Judge` Tool 을 지나고 나서 검증을 하고 난 후에 사용자에게 답변을 뱉는 자동화도 구현해보고 싶습니다. <br>

또한 처음에 해당 파이프라인으로 진행해보려고 생각해 본 `개인 자료 기반으로 직무의 핵심 역량에 맞춰 면접용 포맷으로 경량화 하는 Agent` 를 개발해보고 싶습니다. 
