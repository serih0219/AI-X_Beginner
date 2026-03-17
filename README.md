# 2024-2 AI+X 선도인재양성 기초프로젝트 (with KT) 

2024-2 학기 **AI+X 선도인재양성 기초프로젝트 with KT** 과정에서 수행한 EDA 과제/프로젝트를 정리한 레포지토리입니다.  
데이터를 “그냥 보기”가 아니라, **질문을 세우고 → 검증하고 → 해석까지 연결**하는 흐름으로 정리했습니다.


## What’s inside

- **01 | 지하철 이용 승객 분석 EDA (Team Project)**  
  지하철 승하차 데이터를 기반으로 *요일/시간대/역 특성*에 따라 수요가 어떻게 달라지는지 분석
- **02 | 스마트폰 센서 데이터 EDA (Individual Project)**  
  센서 기반 행동 분류 데이터를 대상으로 *feature 중요도*를 통해 동작 분류에 핵심적인 변수를 탐색

---

# 01. 지하철 이용 승객 분석 EDA (Team Project)

### Goal
지하철 승하차 데이터를 통해 “언제/어디서 승객이 몰리는가?”를 파악하고,  
그 패턴을 **역의 성격(환승/상업지구)** 및 **출퇴근 시간대** 관점에서 해석했습니다.

### Key Findings
- **상업지구 환승역(예: 2호선 잠실역, 가산디지털단지 등)**은  
  **주말보다 주중 이용 승객이 더 많은 경향**이 관찰됨
- “승하차총승객수는 출퇴근 시간대 이용승객수와 관련이 있을까?”라는 질문을 두고,  
  **시간대별 승하차 데이터(외부 데이터)**를 결합해 관계를 확인하는 방향으로 확장

### Deliverables
- 📄 Final Presentation (PDF): `01_subway_ridership_eda/docs/slides/subway_final_presentation.pdf`


---

# 02. 스마트폰 센서 데이터 EDA (Individual Project)

### Goal
스마트폰(또는 웨어러블) 센서 기반 행동 데이터에서  
“어떤 feature가 동작 분류에 핵심적으로 기여하는가?”를 파악하는 데 집중했습니다.

### Approach
- **Feature importance**를 통해 동작 분류에 중요한 변수를 선별
- 동작 라벨을 **정적/동적**, **계단 오르기** 등 다양한 방식으로 정의해  
  *타깃 정의 방식에 따라 중요한 feature가 어떻게 바뀌는지* 비교/탐색

### Deliverables
- 📄 Final Presentation (PDF): `02_child_development_tracking/docs/slides/final_presentation.pdf`

