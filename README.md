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

  <!-- GitHub URL-->
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

[⏱️ Project Duration & 🔧 Tech Stack (기간 및 기술스택)](#projectduration-techstack) <br>

[📊 Data Analysis & Hypothesis (데이터 분석 및 실험 방향성 설정)](#data-analysis) <br>

[🚀 Experimental Progression (실험 과정 및 빌드업)](#experimental-progression) <br>

[🧪 Final SOTA Architecture & Result (핵심 실험과 최종 아키텍처 및 최종결과)](#final-sota-architecture) <br>

[🛠️ Troubleshooting & Engineering (문제 해결 및 인프라 안정화)](#troubleshooting-engineering) <br>

[👥 Team Leadership & Management (팀 리더십 및 협업)](#teamleadership-management) <br>

[📈 Retrospective & Future Work (회고 및 향후계획)](#retrospective-futurework)


<a id="project-overview"></a>

## 🎯 Project Overview
### 프로젝트 배경
과학 상식 도메인에서 사용자의 질문과 이전 대화 맥락을 파악해, 자연스러운 구어체로 정확한 지식을 전달하는 <b>RAG(검색 증강 생성) 기반 챗봇 백엔드 시스템 구축</b>

### 핵심 과제
4,272개의 방대한 지식 베이스 속에서, LLM 의 할루시네이션을 방지하고 정확한 답변을 생성할 수 있도록 <b>가장 관련성 높은 문서를 추출하는 검색(Retrieval) 파이프라인 최적화</b>

### 핵심 평가 지표 및 최적화 목표
단순한 검색을 넘어, RAG 시스템의 <b>비용 효율성</b> 과 <b>답변의 풍부함</b> 을 동시에 달성하기 위해 다음 두 가지 평가지표를 핵심 타겟으로 삼고 성능을 개선했습니다.
  - MRR : LLM 의 토큰 비용을 최소화하고 처리 속도를 높이기 위해, 가장 핵심이 되는 정답 문서를 검색 결과 최상단에 노출시키는 로직 최적화
  - MAP : 복합적인 과학 지식 질문에 대응하기 위해, 단일 문서가 아닌 답변에 필요한 여러 문서를 노이즈 없이 빠짐없이 추출해내는 능력 검증


<a id="projectduration-techstack"></a>

## ⏱️ Project Duration & 🔧 Tech Stack
### ⏱️ Project Duration
- 2026.03.25 ~ 2026.03.31

### 🔧 Tech Stack
| Category | Tech Stack |
| :--- | :--- |
| **Language** | Python 3.10 |
| **RAG Framework** | HuggingFace, sentence-transformers |
| **Search Engine** | Elasticsearch 8.x (Dense & Sparse Hybrid Search) |
| **NLP Tool**| kiwipiepy (KiWi 형태소 분석기) |
| **LLM & Embedding - Generation** | gpt-4o, gpt-4o-mini, Solar |
| **LLM & Embedding - Retrieval** | BAAI/bge-m3 (Embedding) |
| **LLM & Embedding - Reranking** | BAAI/bge-reranker-v2-m3 (Cross-Encoder) |
| **Data Analysis** | Pandas, Numpy, Scikit-learn |
| **Environment** | Ubuntu OS, Local GPU Server(CUDA - RTX3070) |

<a id="data-analysis"></a>

## 📊 Data Analysis & Hypothesis
초기 베이스라인(단순 Vector DB 검색 + LLM 생성) 파이프라인의 한계를 극복하기 위해, 또한 직관이 아닌 통계적 근거를 바탕으로 해결하고자 가장 먼저 4,272개의 과학 지식 문서와 질의 데이터의 통계적/언어적 특성(EDA)을 분석하여 최적화 전략을 수립했습니다.

### Insight 1. 텍스트 임베딩 단독 검색의 한계와 하이브리드 최적화
<img width="2017" height="886" alt="Image" src="https://github.com/user-attachments/assets/ae17f40c-010c-43a1-ab4c-242e89b83a7a" /> <br>

- 분석 : BGE-M3 와 Solar 임베딩 모델의 벡터 공간을 시각화하여 분석한 결과, 과학 도메인의 전문 용어들이 밀집되어 있어 의미론적(Dense) 유사도만으로는 정확한 문서 변별이 어려운 구간을 확인했습니다.
- 실험 방향 : Dense Retrieval 단독 수행 시 검색 해상도가 떨어질 것이라 판단하여, 키워드 매칭(Sparse)을 결합하는 하이브리드 아키텍처를 베이스로 삼고 <b>최적의 결합 비율(RRF 가중치)</b> 을 찾기 위한 실험을 계획했습니다.

---

### Insight 2. 지식 베이스 내 중복 및 유사 데이터 처리
<img width="686" height="235" alt="Image" src="https://github.com/user-attachments/assets/163cec70-9a44-4e47-aca5-93bae5e3ab8c" /> <br>

- 분석 : 전체 문서를 Table 형태로 뽑아서 비교해 본 결과, 전체 데이터에서 내용이 거의 동일하거나 오타로 인해 중복 생성된 데이터가 다수 존재함을 발견했습니다. 이러한 중복 데이터가 존재할 경우, 검색기가 유사한 문서 여러 개를 동시에 상위권에 올리게 되어 LLM의 컨텍스트 창을 낭비하고 결과적으로 답변에 생성에 필요한 다른 유익한 정보들이 누락되는 현상이 발생 할 수 있다고 생각했습니다.
- 실험 방향 : 중복 문서를 식별하여 하나로 그룹화하거나 검색 결과에서 상위 K개 내에 중복된 내용이 들어 오지 않도록 제어 로직을 구성해야 겠다는 필요성을 도출했습니다.

---

### Insight 3. 문서 길이 분포에 따른 파편화 리스크 도출
<img width="790" height="490" alt="Image" src="https://github.com/user-attachments/assets/eb659f22-40de-47fe-8189-bba0c8ad18b1" /> <br>

- 분석 : 4,272개의 문서의 길이를 EDA 해본 결과, 대부분의 문서가 특정 글자 수(약 200~400자) 구간에 집중되어 있고 하나의 문서가 곧 압축된 하나의 지식 단위임을 파악했습니다.
- 실험 방향 : 무분별한 문서 쪼개기(Chunking)는 오히려 유사도 랭킹을 꼬이게 만드는 'Top-K 밀림현상' 을 초래할 수 있다는 생각과 시스템 리소스만 낭비할 수 있겠다 라는 생각을 하게되었습니다. 따라서, 원문을 쪼개지 않고 전체를 색인해서 <b>재현율(Recall) 을 극대화 하고 리소스를 줄여보자</b> 라는 전략을 세워보려고 했습니다.

---

### Insight 4. 형태소 분석기(KiWi) 기반의 정밀 토큰화 전략
- 분석 : "~~ 하지 않는 이유" 와 같은 핵심 부정 문구가 일반적인 분석기에서 "이유" 로만 토큰화되어 검색 결과가 정반대로 나오는 리스크를 확인했습니다.
- 실험 방향 : 한국어 특화 분석기인 `Kiwi` 를 채택하고, 전문 용어 및 부정형 표현이 훼손하지 않도록 `Stoptags` 를 정밀하게 제어하는 전처리 실험을 진행하고자 했습니다.


<a id="experimental-progression"></a>

## 🚀 Experimental Progression
높은 평가지표 Score 를 달성하기 위해, 총 12단계의 점진적인 실험을 거치며 검색 성능과 시스템 안정성을 고도화 했습니다.

### Phase 1. 기초 환경 구축 및 할루시네이션 제어
- 초기 구축 : 기본적인 Vector DB 와 LLM 을 연동한 RAG 형태의 베이스라인 파이프라인을 구축했습니다.
- Self-Correction (자가검증) 도입 : 초기 모델이 검색된 문서를 무시하고 자신의 내재 지식으로 답변을 지어내는 할루시네이션 현상을 발견했습니다. 따라서 이를 제어하기 위해 프롬프트 단어에 '반드시 제공된 문서에 기반하여 답변을 스스로 검증하라' 는 Self-Correction 로직을 추가하여 답변의 신뢰도를 확보했습니다.

---

### Phase 2. 검색 해상도 극대화 및 파이프라인 안정화
- HyDE(가상 문서 생성) : 과학 도메인 특유의 어휘 불일치 문제를 해결하기 위해, 사용자 질의에 대한 가상의 답변을 먼저 생성하여 검색 키워드를 확장하는 HyDE 기법을 도입해 재현율(Recall)을 대폭 끌어올렸습니다.
- CleanText 및 Few-shot 최적화 : 보이지 않는 특수/제어 문자로 인해 발생하는 JSON 파싱 에러 를 방어하기 위해 전처리/후처리 정제 파이프라인을 구축했습니다. 또한 Few-shot 프롬프팅을 통해 챗봇의 구어체 톤앤매너를 일정하게 규격화 했습니다.

---

### Phase 3. 팀 내 SOTA Score 달성 및 한계 돌파 탐색
- Model Edit : 이전 단계의 최적화 로직들을 결합하고, 백본 언어 모델 및 임베딩/리랭커 모델의 조합을 최적화한 8번째 실험에서 "최종 1위 스코어" 를 달성했습니다.
- 성능 한계 돌파를 위한 추가 탐색 : SOTA 달성 이후에도 검색 품질을 더 높이기 위해 동적 문서 추출(Dynamic K), 한국어 특화 임베딩(Solar), 다중 질의 확장(Multi-Query), RRF 가중치를 1:1 이 아닌 2:1, 1:2 처럼 여러가지 가중치 부여 등 다양한 변인을 통제하며 추가 실험을 진행했습니다.
- LLM-as-a-Junge 구축 : 대회 플랫폼의 1일 제출 횟수 제한이라는 병목을 극복하기 위해, LLM 이 직접 검색된 문서와 생성된 답변의 관련성을 채점하는 로컬 평가 시스템(Judge)을 자체 구축하여 실험의 사이클을 가속화했습니다. 


<a id="final-sota-architecture"></a>

## 🧪 Final SOTA Architecture & Result
수많은 실험 끝에 도달한 최종 파이프라인 (실험-8번)은 검색 엔진의 한계와 LLM의 불안정성을 상호 보완하도록 설계된 지능형 RAG 아키텍처 입니다. <br>
<img width="2816" height="1536" alt="Image" src="https://github.com/user-attachments/assets/aa4040b3-88b0-477d-8bf9-71469221c1a4" /> <br>

### 1. 지능형 라우터
- `gpt-4o-mini` 를 활용하여 사용자의 입력이 단순 일상 대화(ChitChat)인지, 과학 지식이 필요한 정보성 질의인지 완벽히 분류하여 불필요한 검색 엔진 과부하를 방지했습니다.

### 2. 문맥 확장을 위한 HyDE
- 질문의 핵심 키워드가 부족할 경우를 대비해 가상의 정답 문서를 사전 생성하여 검색 쿼리의 의미적 풍부함을 극대화 했습니다.

### 3. 비대칭 하이브리드 검색 (HyBridSearch & RRF)
- `BAAI/bge-m3` 기반의 Dense 검색(의미 매칭)과 형태소 분석기 기반의 Sparse 검색(키워드 매칭)을 동시 수행합니다. 데이터 특성을 반영해 최적의 비율로 RRF를 적용, 1차적으로 노이즈가 제거된 Top-3o 문서를 추출합니다. <br>
이 때 여러가지 실험을 진행하면서 찾은 RRF 최적의 비율은 1:1 이였습니다.

### 4. 교차 평가 리랭킹
- 추출된 30개의 문서에 대해 `BAAI-bge-reranker-v2-m3` 를 적용하여, 질문과 문서의 문맥을 밀도 있게 교차 평가하고 최종적으로 가장 완벽한 Top-3 정답 문서를 선별합니다.

### 5. 자가 검증 기반 생성기
- `gpt-4o` 모델을 활용해 구어체 답변을 생성합니다. 이때 프롬프트 엔지니어링을 통해 LLM 의 내재 지식 맹신을 차단하고, 검색된 문서에만 근거하도록 강제하는 '자가 검증(Self-Correction)' 을 거쳐 최종 출력문을 반환합니다.

### 🏆 Final Performance & Leaderboard
- MAP (Mean Average Precision) : 0.9242 
- MRR (Mean Reciprocal Rank): 0.9318

<img width="980" height="288" alt="Image" src="https://github.com/user-attachments/assets/9c4bdf7d-1810-4082-af41-ad5fac36c439" /> <br>
Rank: 🥇1st


<a id="troubleshooting-engineering"></a>

## 🛠️ Troubleshooting & Engineering
### 1. 데이터 소스 분석을 통한 라우팅 기준 재설정 및 성능 돌파
#### 문제 정의
자체 평가 파이프라인 분석 중, 라우터가 '공교육 지출 현황' 이나 '통학 버스의 가치' 등 과학과 무관한 질문을 정보성 질의로 오분류하여 정답을 생성하는 현상을 발견했습니다.

#### 원인 분석
오분류된 데이터가 정답으로 생성하는 케이스와 오분류된 데이터를 강제로 탈락시켜 정답을 생성하는 케이스를 모두 리더보드에 재출해 본 결과, <b>오히려 오분류된 데이터를 강제로 탈락시키는 케이스가 Score 가 하락하는 점</b> 을 발견했습니다.
이 기현상을 역추적해서 제공된 데이터의 기원을 분석해 본 결과, 학습 데이터로 제공된 데이터 기반이 되는 `Ko-H4 (MMLU, ARC)` 벤치마크가 순수 과학뿐만 아니라 경제, 사회학 등 광범위한 '지식' 전반을 정답으로 취급하고 있음을 판단했습니다. 따라서 오분류된 데이터가 정답으로 생성하는 케이스 Score 가 더 높은 것을 보아 리더보드에서 평가하는 Private Test Data 또한 데이터 근간이 학습 데이터와 동일하겠구나 라는 추측을 했습니다.

#### 해결 방안
기존의 '과학 상식 vs 일상대화' 분류 기준을 일단 폐기하기로 결정했습니다. 라우터의 프롬프트와 분류 기준을 'MMLU/ARC 수준의 정보성 지식 vs 단순 일상 대화' 로 재설계하여, 테스트 데이터의 본질에 맞게 RAG 파이프라인의 필터링 타겟을 교정했습니다.

#### 인사이트
복잡한 모델 아키텍처 튜닝 이전에 <b>데이터의 생성 배경과 통계적 특성을 얼마나 완벽히 이해하고 통제하느냐</b> 가 성능을 좌우한다는 `Garbage In, Garbage Out` 을 다시 한번 뼈저리게 느낄 수 있었습니다.

---

### 2. 대형 LLM 의 지식 맹신 현상 제어 및 프롬프트 최적화
#### 문제 정의
파이프라인의 답변 생성 단계에서 모델 성능을 극대화하기 위해 기존 모델을 대형 모델(gpt-4o)로 교체했으나, 오히려 리더보드 Score가 하락하는 현상이 발생했습니다. 또한, 답변의 품질을 높이고자 프롬프트 조건을 매우 엄격하게 설정했을 때도 오히려 결과가 저하되는 부분을 볼 수 있었습니다.

#### 원인 분석
1. LLM Arrogance : 모델 체급이 커질수록 사전 학습된 자신의 내재 지식을 맹신하는 성향이 강해짐을 확인했습니다. 이로 인해 필수적인 외부 문서 검색(RAG) 결과를 무시하고 임의로 할루시네이션이 섞인 답변을 생성하는 것이 점수 하락의 주원인 이라 판단하였습니다.
2. Prompt 경직성 : 너무 강하게 쥐어진 프롬프트 제약은 언어 모델 본연의 유연한 추론 능력을 억압하여 오히려 문맥에 맞지 않는 부자연스러운 답변을 유도했습니다.

#### 해결 방안
파이프라인 각 단계별 모델 성향에 맞춰 제어 수준을 다각화 했습니다. `gpt-4o` 에는 "정답을 알더라도 반드시 검색된 외부 문서를 기반으로 대답할 것" 과 같은 자가 검증 제약을 명확히 부여하여 검색 맹목성을 높이고, 불필요한 제약 조건들을 걷어내어 모델이 자연스러운 구어체를 생성할 수 있는 유연성을 보장하려고 했습니다.

#### 인사이트
모델의 체급이 무조건적인 성능 향상을 보장하지 않음을 체감했습니다. 모델 고유의 성향을 파악해서 적재적소에 배치하고, 과도한 통제보다 '검색 의존성' 과 '추론 유연셩' 사이의 적절한 프롬프트 밸런스를 찾는 것이 프롬프트 엔지니어링의 핵심임을 깨닫게 되었습니다.

---

### 3. 직관 오류 극복: 하이브리드 검색의 RRF 가중치 최적화
#### 문제정의
하이브리드 검색(Dense + Sparse) 결합 시, 전문 용어가 중요한 과학 도메인의 특성을 고려해서 형태소/키워드 분석인 `Sparse` 에 더 높은 가중치를 부여하면 검색 해상도가 훨씬 높아지겠다 라는 가설을 세우고 진행해봤지만, 실제 평가 점수는 하락했습니다.

#### 원인분석
특정 검색기에 극단적인 가중치를 부여해 본 결과, 동의어나 문맥적 유사성을 통해 유연하게 정답을 찾아야 하는 Dense Retrieval 의 강점이 묻히고 랭킹 산정의 밸런스가 붕괴되는 부작용이 발생했습니다.

#### 해결 방안
비대칭 가중치를 버리고, 가장 밸런스가 좋은 1:1 동등 비율로 가중치를 원복하고, 대신 부족한 키워드 커버는 가상 정답 문서 생선(HyDE) 기법을 통해 보완하여 두 검색기가 온전히 상호 보완적으로 작동하도록 아키텍처를 수정했습니다.

#### 인사이트
하이퍼파라미터 튜닝 시 편견이나 직관에 의존하는 것의 위험성을 배웠던 것 같습니다. RAG 시스템의 앙상블 결합에서는 각 모듈이 가진 장점을 훼손하지 않는 안정적인 밸런스를 유지하는 것이 최종 시너지를 극대화하는 가장 확실한 방법임을 Score 지표를 통해 확인할 수 있었습니다.


<a id="teamleadership-management"></a>

## 👥 Team Leadership & Management
코드 병합 중심의 개발보다, <b>실험 결과와 인사이트의 병합</b> 이 중요한 프로젝트 특성에 맞춰 다음과 같은 엄격한 연구 협업 룰을 세팅하고 리드했습니다.

1. 1일 1회 리더보드 제출 : 완벽함을 챙기려고 매번 실험만 반복하는 것을 방지하고, 매일 정량적 지표를 확인하면서 파이프라인의 방향성을 수정하도록 강제했습니다.
2. 데이터 기반 소통 규칙 : 추상적인 텍스트 공유를 금지하고, EDA 결과나 실험 인사이트를 Slack 공유할 때 시각화 된 데이터를 첨부하도록 규정하여 팀 내 커뮤니케이션의 객관성을 확보했습니다.
3. 프로젝트 인사이트 공유 규칙 : 매일 수업 정규 시간 종료 전, 각자가 개별적으로 파이프라인 실험 결과와 성능 향상 로직을 투명하게 공유하여, 성공적인 실험 요소들이 팀원 전체의 파이프라인에 참고할 수 있도록 리드했습니다.


<a id="retrospective-futurework"></a>

## 📈 Retrospective & Future Work
### 📌 회고
이번 RAG 프로젝트를 통해서 지금까지 진행했던 대회랑 다른 파이프라인과 개념을 접하면서 RAG 파이프라인이 무엇을 의미하고 이 기술에는 어떤 개념들이 존재하는지 알게 된 소중한 프로젝트 였던 것 같습니다. <br>

이런 꾸준한 실험을 하고 평가지표를 얻는 프로젝트를 진행하면서 주어진 프로젝트 일정이나, 프로젝트를 통해 주최자의 의도 (어떤 주제를 주고 어떤 형식의 데이터를 주면서 어떤 방법을 요구하는지에 대한 의도를 의미합니다) 를 조금 파악해보면서 프로젝트와 관련된 여러가지 실험을 진행해보려고 하는데 이번 프로젝트에서는 기간이 짧았던 이유가 RAG 파이프라인 자체에서는 이미 성능향상으로 이어지는 부분이 고착화 되어 있는 요소가 많아서 짧은 기간에 실험할 수 있는 요소가 어느정도 정해져 있어 이렇게 짧게 잡힌게 아닌가 라는 생각이 들었습니다. <br>

실제로 다른 실험을 진행했던 프로젝트보다 RAG 파이프라인 성능향상 기법으로 다루는 파이프라인이 어느정도 고착화 되어 있음을 알 수 있었고, 실제로 여러가지 요소가 정리되어 있는 학습블로그가 많이 정리된 부분을 접했던 것 같습니다. <br>

이번에 느끼고 배운 파이프라인을 통해 다음 대회에 기반으로 가져갈 수 있는 좋은 경험을 했던 것 같습니다.

### 📗 향후계획
프로젝트 상에서 Data 에 대한 오류가 존재했기 때문에, 다음번에는 Task 에 맞는 Data 를 구성해서 RAG 파이프라인을 구현해보고 싶습니다. <br>

또한 파이프라인을 학습하면서 파이프라인 자체가 파인튜닝이랑 비슷한 느낌이 들었지만, 일정 도메인에 대한 전문 가이드를 실질적으로 DB 에 잘 적재만 할 수 있다면 파인튜닝보다는 비용을 절감하면서 효율적인 도메인 전용 파이프라인을 구성 할 수 있겠다 라는 생각이 들었습니다. 따라서 이번에 배운 파이프라인을 통해 특정 도메인에 특화 된 백엔드 시스템을 구축해보는 것이 목표입니다.
