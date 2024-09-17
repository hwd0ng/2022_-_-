# 2022_Gyeonggi_Economic_Visualization_IdeaContest
### 2022 경기지역경제포털 빅데이터활용 시각화 아이디어 공모전
#### - 지역경제 관련 정보를 활용하여 지역경제 및 지역산업 특징을 파악할 수 있는 대시보드 구성
<hr width="800">

<img width="800" alt="image" src="https://github.com/user-attachments/assets/0c923c67-4434-47ed-a708-ec31d8e28361">
<hr width="800">

### 1. Dataset
- [연령별 거주인구 대비 지역화폐 사용금액 현황.csv](https://bigdata-region.kr/#/dataset/9d8c20d9-a9ca-4687-b3de-ade09d5664c1)
- [연령별 지역화폐 사용 빈도 현황.csv](https://bigdata-region.kr/#/dataset/e6681bd5-8ab5-4ab1-a764-91e4a394fbf0)
<img width="800" alt="image" src="https://github.com/user-attachments/assets/eecfce30-e20e-4d94-aee9-947ed12226d7">
<hr width="800">

### 2. 시각화 아이디어
- 경기도 지역 내 지역화폐 사용금액과 인구 데이터에 대한 시각화 (상위 다섯 지역)
- 지역화폐 사용금액과 인구와의 상관관계 파악 (0.506)
- 월별 지역화폐 사용금액 추세 (우상향)
- 지역화폐 종류별 사용빈도 파악 후 지도 시각화
  
   <details>
   <summary><strong>시각화 결과 보기/접기</strong></summary>
   <img width="959" alt="image" src="https://github.com/user-attachments/assets/ff42c2de-3551-4b8d-a636-415f4908e431">
   <img width="946" alt="image" src="https://github.com/user-attachments/assets/d383e8b6-a51c-4df3-b317-9bad0b19d589">
   <img width="959" alt="image" src="https://github.com/user-attachments/assets/0956275f-7973-4752-989b-5ceee3f1f2a2">
   <img width="935" alt="image" src="https://github.com/user-attachments/assets/d05cb819-30e6-4702-a50e-85d98f6bcbb0">
   <img width="952" alt="image" src="https://github.com/user-attachments/assets/cd4c0df7-9f97-4918-ac18-7049c50ed196">
   <img width="902" alt="image" src="https://github.com/user-attachments/assets/f05eee2d-0d6a-495a-8677-5bd3c90bf9dd">
   <img width="956" alt="image" src="https://github.com/user-attachments/assets/a10838db-574a-4d6e-9a50-880b956eea2f">
   <img width="855" alt="image" src="https://github.com/user-attachments/assets/bc9bb231-4eb3-4385-9136-b1a5b9d3d86d">
   </details>
<hr width="800">
  
### 3. K-means 군집분석
- Elbow Method를 통한 군집 개수 결정
- 경기도 내 42개의 시군구를 4개의 군집으로 분류
- 군집 별 특징 파악 (사용금액, 인구)
- 군집 별 해당 지역 확인
  
   <details>
  <summary><strong>군집분석 결과 보기/접기</strong></summary>
   <img width="819" alt="image" src="https://github.com/user-attachments/assets/4039ee1f-fb29-457d-b2ab-94d5358a7b74">
   <img width="788" alt="image" src="https://github.com/user-attachments/assets/b05acb4c-045d-4576-aced-e89183d26e4d">
   <img width="913" alt="image" src="https://github.com/user-attachments/assets/ed3d70dc-a68b-4a1c-b9f4-db09d573b639">
   <img width="876" alt="image" src="https://github.com/user-attachments/assets/ee0cad68-e068-47d4-b4b1-3af161d8081e">
   </details>
<hr width="800">

### 4. 결론
- 경기도 지역 내 지역화폐 사용금액 및 인구에 대한 여러 정보를 시각화해서 파악해보고 군집분석을 통해 지역별로 어떤 특징들을 가지고 있는지 확인해 볼 수 있다.
- 나아가서 인구가 많음에도 지역화폐 사용금액이 적은 지역, 혹은 인구도 적고 지역화폐 사용금액도 적은 지역의 공통적인 원인에 대한 조사도 이루어진다면
  추후 지역화폐 정책과 경기도 지역 경제활성화에 대한 긍정적인 방향을 제시할 수 있을 것이다.
<hr width="800">

## 맡은 역할
- 팀의 조장으로서 공모전에 적합한 아이디어를 모아 주제를 선정하고 적절한 데이터셋을 수집했습니다.
- 지역화폐 사용금액과 인구와의 상관관계를 파악하여 시각화하였습니다.
- 지역별로 가장 많이 쓰이는 지역화폐를 한 눈에 알 수 있도록 지도에 시각화를 하였습니다.
- K-means 군집분석을 활용하여 지역화폐 사용금액과 인구 사이의 특징을 4개의 군집으로 분류하였습니다.
- 전체적인 내용을 종합해 PPT 제작 후 공모전 1차 통과후 발표심사에서 발표를 맡았습니다.

## 프로젝트 후기
- Python을 처음 접해보는 실습 수업에서 진행한 프로젝트다보니 조원 모두가 Python 언어에 능숙하지 못해서 코드를 짜는데 어려움이 있었지만
  다같이 아이디어를 내보고 서칭하는 과정에서 Python으로 시각화하는 여러 방법들에 대해서 단기간에 배울 수 있었습니다.
- 공모전 특성 상 "경기지역포털" 내에 데이터셋을 활용해야 한다는 점에서 다양한 데이터를 모으기 어려웠지만 아이디어를 잘 선정해서 만족스럽게 진행되었습니다.
- 텍스트와 숫자로만 되어 있는 데이터셋을 가지고 matplotlib와 seaborn 라이브러리를 통해 막대그래프, 테이블표, 원그래프 등 여러가지 시각적인 결과물을 내는 것이 흥미롭고 재밌었습니다.
- folium 라이브러리를 활용하여 경기도 지역을 표시하는 부분에서 헤메기도 했지만 geojson파일을 활용하여 해결할 수 있었습니다.
- 이 공모전은 대학교 수업시간에 시각화 실습 수업을 진행하던 중 교수님께서 공모전에 나가서 1차 예선통과 라도 하면 학점을 한 단계 올려준다는 말씀에 나가게 되었는데 실제로 1차 통과를 하게 되어서 너무 기뻤습니다.
- 혼자였으면 이렇게까지 결과를 못 냈을 거라는 생각이 들었고 Python을 처음 배우는 사람끼리 이렇게 협업을 해서 좋은 결과를 낼 수 있어서 만족스러웠던 프로젝트였습니다.
