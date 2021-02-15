# train_machinelearning
### 2019-2 종합프로젝트1 with machine learning

2019-2 경북대 종합설계프로젝트1로 진행한 프로젝트  
📄 감정 인식 알고리즘 기반의 청중 반응 분석 시스템 재구성

### 1. 머신러닝을 적용해 최적의 분류 모델 찾기
  - decision tree
  - random forest
  - gradient boosting
  
  - decision tree accuracy: 0.686
  - random forest accuracy: 0.653
  - gradient boosting accuracy: 0.678
  
  - 위 프로젝트에서 공식을 만드는 데 쓴 데이터를 train/valid data로 썼고, 검증하는 데이터로 이용한 데이터를 test data로 사용
  - 검증 데이터는 6개의 영상에 각각 8명의 감정 데이터로 이루어져 있음. 8명의 피실험자가 각 영상에서 느낀 감정을 positive, normal, negative로 나누어 판단했고, 이를 기준으로 얼마나 예측을 잘 했는지 보려했는데 잘 되지 않았음.
  
  - 데이터를 다시 봤을 때, train/valid 데이터의 형태와 test data가 많이 형태가 다름.. normalization?을 해서 적용해야할까?

### 2. 딥러닝 적용해보기

