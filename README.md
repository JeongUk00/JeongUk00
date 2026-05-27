# 김정욱 (JeongUk Kim)

<img src="https://github.com/user-attachments/assets/de0f2004-304e-4cca-8950-eedfea8b5e90" width="180"/>

## 👤 About Me

- 학력 | 홍익대학교 산업데이터공학과 졸업
- 자격 및 활동 | 정보처리기사 · ADsP (데이터 분석 준전문가) · SQLD · KT Aivle School AI Track
- Email | jeongwook@gmail.com
- Blog | [기술 블로그](https://jwkim0826.tistory.com/)
- GitHub | [GitHub](https://github.com/JeongUk00)

### Data Analysis & AI Engineer

#### Introduction
> 1. 데이터를 단순히 다루는 것을 넘어, **근거를 끝까지 추적하는 집요함**이 있습니다.
>    - "왜 이 변수가 중요한가", "왜 이 모델이 더 잘 작동하는가"를 설명하지 못하면 분석이 완성됐다고 생각하지 않습니다. 산업데이터공학과에서 배운 통계적 사고를 바탕으로, 직관보다 수치와 근거를 먼저 찾습니다.
> 2. **추상적인 인사이트보다 구체적이고 검증 가능한 결과**를 만들려고 노력합니다.
>    - "성능이 향상됐다"가 아니라 "정확도가 87%에서 92%로 올랐고, 그 원인은 피처 X의 전처리 방식 변경이었다"처럼 재현 가능한 분석을 지향합니다.
> 3. 분석 결과를 **누구나 이해할 수 있는 언어로 전달**하는 것을 중요하게 생각합니다.
>    - 기술적인 내용을 비전공자도 납득할 수 있도록 시각화하고 설명하는 연습을 하고 있습니다.
> 4. 문제를 풀기 전에 **문제를 올바르게 정의하는 것**에 집중합니다.
>    - 데이터 분석에서 가장 많은 시간을 낭비하는 구간은 잘못된 문제를 열심히 푸는 것이라고 생각합니다. EDA 단계에서 충분히 데이터를 탐색하고 가설을 세운 뒤 모델링에 진입하는 방식을 습관으로 삼고 있습니다.

> 숫자 속에서 의미를 찾는 과정을 좋아합니다. 단순히 모델을 돌리는 것보다, 왜 이 데이터가 이런 패턴을 보이는지 — 그 원인을 끝까지 파고드는 편입니다.  
> 분석 결과가 실제 의사결정에 쓰일 수 있도록 정리하고 전달하는 것도 중요하게 생각합니다.

---

## 🛠️ Tech Stack

**Data Analysis & ML,DL**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**AI / LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-007ACC?style=flat-square&logoColor=white)

**Data Engineering & Tools**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

---

## 🗂️ Projects

### ✈️ 항공기 고객 만족도 예측
> `Python` `XGBoost` `DNN` `EDA`

**기간** | 26.04.14 ~ 26.04.20

**역할** | 서기 (코드 정리)

항공사 고객 데이터에서 만족도를 예측하는 이진 분류 모델을 구축했습니다.
데이터의 90%가 '만족'으로 편향된 불균형 문제를 발견하고, Class Weight와 Oversampling을 비교 실험해
Macro F1-score 0.93 · class 0 Precision 0.77 → 0.95 향상을 달성했습니다.

| 문제 정의 | 단순 정확도만으로는 실제 불만족 고객을 놓치는 비즈니스 리스크 존재 → Recall 중심의 성능 개선이 핵심 과제 |
|:---|:---|
| **사용 기술** | Python · DNN · XGBoost · Class Weight · Oversampling · EDA · 카이제곱 검정 |
| **결과물** | Class Weight 적용 DNN 모델 / Macro F1-score 0.93 / class 0 Precision 0.77 → 0.95 |

<details>
<summary>💡 배운 점</summary>

처음엔 Accuracy 0.97이 나왔을 때 잘 됐다고 생각했는데, 알고 보니 모델이 그냥 다 '만족'으로 찍어버린 거였습니다.
데이터 불균형을 직접 마주하면서 숫자 하나에 안심하지 말고, 어떤 지표를 봐야 하는지부터 고민해야 한다는 걸 체감했습니다.
Class Weight와 Oversampling을 비교 실험하면서 문제 상황에 맞는 전략을 고르는 과정이 생각보다 훨씬 중요하다는 것도 배웠고요.
코드 정리 역할을 맡으면서 단순히 돌아가는 코드가 아니라, 나중에 봐도 이해할 수 있는 코드를 쓰는 습관도 같이 들이게 됐습니다.

</details>

[📁 repo](https://github.com/JeongUk00/airline-customer-satisfaction-prediction.git)

---

### 🎓 AI 강사 Agent
> `Python` `LangGraph` `GPT-4o-mini` `TTS` `Gradio`

**기간** | 26.04.24 ~ 26.04.28

**역할** | 발표자

PPT 파일 하나를 업로드하면 강의 스크립트·음성·영상을 자동 생성하는 AI Agent를 구현했습니다.
슬라이드 파싱 → 웹 검색 → 스크립트 생성 → TTS → 자막 합성 → MP4 출력까지 풀 파이프라인을 구축하고,
퀴즈 자동 생성 및 사용자 피드백 기반 스크립트 수정 기능을 포함했습니다.

| 문제 정의 | 슬라이드 수정 시마다 스크립트·녹음·편집을 처음부터 반복해야 하는 비효율 → AI로 제작 과정 전체를 표준화 |
|:---|:---|
| **사용 기술** | Python · LangGraph · GPT-4o-mini · TTS · ChromaDB · Tavily · FFmpeg · Gradio |
| **결과물** | PPT → MP4 풀 파이프라인 / 퀴즈 자동 생성 / 사용자 피드백 기반 스크립트 수정 |

<details>
<summary>💡 배운 점</summary>

처음엔 "LLM한테 PPT 던져주면 알아서 잘 하겠지"라고 생각했는데, 실제로는 파싱 → 검색 → 생성 → 변환 → 합성까지
각 단계가 제대로 연결되지 않으면 아무것도 안 된다는 걸 몸으로 배웠습니다.
LangGraph로 노드를 직접 설계하면서 Agent가 단순히 LLM을 감싸는 게 아니라 상태를 관리하고 흐름을 제어하는 구조라는 게 실감 났고요.
사용자 피드백으로 스크립트를 수정하는 기능을 붙이면서, 모델 성능만큼이나 사용자가 개입할 수 있는 여지를 어디에 둘지 설계하는 것도 중요하다는 걸 느꼈습니다.

</details>

[📁 repo](링크)

---

### 🛍️ 상품 리뷰 분석 Agent
> `Python` `LangGraph` `LangSmith` `Streamlit`

**기간** | 26.05.11 ~ 26.05.14

**역할** | 조장

고객 리뷰를 자동으로 분석·요약해 비즈니스 인사이트까지 제공하는 다중 에이전트 파이프라인을 구축했습니다.
리뷰 400건 기준 수동 26-33시간 → AI 13분으로 **처리 속도 98-99% 단축**, 비용 약 **99.8% 절감**을 달성했습니다.

| 문제 정의 | 리뷰 증가 속도를 인력이 따라갈 수 없고, 오류 추적도 불가 → 자동화 파이프라인 + 모니터링 체계로 해결 |
|:---|:---|
| **사용 기술** | Python · LangGraph · LangSmith · GPT-4o-mini · Streamlit · ChromaDB · HITL |
| **결과물** | 처리 속도 98-99% 단축 / 비용 99.8% 절감 / Streamlit 대시보드 + Insight Agent 자동 리포트 |

<details>
<summary>💡 배운 점</summary>

LangSmith를 처음 붙여봤는데, 단순히 로그 보는 도구가 아니라 "어느 노드에서 왜 틀렸는지"를 추적할 수 있어야
실제로 고칠 수 있다는 걸 느꼈습니다.
HITL 노드를 설계하면서는 AI가 판단하기 애매한 케이스를 억지로 자동화하려다 오히려 품질이 떨어진다는 것도 배웠고요.
에이전트를 여러 개 연결하다 보니 각각이 잘 돌아가도 연결부에서 무너지는 경우가 생겨서,
모듈 설계를 처음부터 꼼꼼히 잡는 게 얼마나 중요한지 실감했습니다.

</details>

[📁 repo](링크)

---

*"데이터에서 인사이트를, 그리고 그 인사이트가 실제로 쓰이도록."*

![Programmers Badge](https://raw.githubusercontent.com/JeongUk00/Programmers_Badge_Generator/main/result/result.svg)
