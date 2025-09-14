# secom-dataset-project
uci-secom dataset defect 감지 ML model 비교

# 전처리
sensortime 제거


sensor간 상관계수 75% 이상 sensor 제거


pass_fail 상관계수 top 40 선정

# 분류 / SMOTE / SMOTEENN
train_test_split 진행


기법 간 비교를 위해 SMOTE 기법과 SMOTEENN 기법 모두 진행

# 모델 구축
SVC + SMOTE AND SMOTEENN


RF + SMOTE AND SMOTEENN


XGB + SMOTE AND SMOTEENN

# Result
Acccuracy -> SMOTE


Defect detectability -> SMOTEENN 
