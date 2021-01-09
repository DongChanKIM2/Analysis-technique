# Analysis-technique
## 분석 기법

### 01 Blending의 AutoML
+ 한 번에 15개의 모델로 분석가능해 시간절약
+ 15개의 모델 中 정확성 높은 모델 확인 후 Blending or 정확성 높은 분석기법 사용 가능
+ TIP: 곡선형태의 Smooth한 모델은 고전적인 분석기법, 0 or 1과 같이 바뀌는 모델은 tree알고리즘이 좋음

### 02 단어 빈도수 Counting
+ itertools를 활용해 단어수 Counting
+ EDA용도로 사용하면 편리

### 03 업무시간을 단축시켜주는 GroupBy
+ GroupBy를 활용해 장소, 시간대별로 정렬 가능
+ 이 기능을 활용해 인턴 당시에 기상청 데이터 4년치 데이터를 년,월,일별로 빠른 시간안에 처리할 수 있었습니다.

### 04 데이터 익명처리하는 Masking
+ Masking 기법을 활용해 민감한 정보들 익명화할 수 있습니다.
