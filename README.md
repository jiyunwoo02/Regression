# Regression
2023.11.8~2023.11.16 까지 진행한 코드와 데이터
보고서 업로드

1. 일상생활에서 볼 수 있는 Odds 사례를 한 가지 찾아보고 설명하시오.

2. 선형회귀분석, 로지스틱회귀분석 각 수행

   
   2.1 (데이터 수집 및 전처리)
   
         - 데이터 수집은 아래의 UCI data repository에서 검색   
           . https://archive.ics.uci.edu/   
         - 단, 선형회귀분석과 로지스틱회귀분석에 적합한 각 데이터를 사용할 것 (변수 15개 이상)   
         - 범주형 변수(categorical variable)를 적절하게 변환 처리할 것 (Categorical -> Numerical)   
         - 필요한 상황에 따라 스케일링(Scaling) or 정규화(Normalization) 수행   
         - 학습데이터(training data)와 검증데이터(validation data), 그리고 테스트데이터(test data)로 구분 (예시. 7:1:2)
    
   2.2 (탐색적 데이터 분석) 데이터 내재적인 특징 가시화    
        - 수업시간에 배운 bar plot, scatter plot, pie chart, histogram, correlation matrix 등 데이터 특징을 인지할 수 있도록 가시화
    
   2.2 (학습모델 구축) 모델 구축 및 해석 (예시. 잔차, 변수 별 계수 및 p-value, adj. R^2, 모델 유의성 F검정 등 수업에서 학습한 내용 일체)
   
   2.3 (선형회귀 결과해석) 예측결과로 MSE(Mean squared error), MAE(Mean absolute error)를 측정하고 설명하시오.    
        - 또한, 선형회귀에 대한 분석 가시화 residual plot, QQ plot, Residual vs Fitted plot 등 그리고 각 그림에 대해 올바르게 해석할 것    
    
   2.4 (로지스틱회귀 결과해석) 예측결과로 confusion matrix와 recall, precision, F1 measure를 측정하고 설명하시오.
   
   2.5 (공통) 회귀와 분류모델에 대해서 선형성(linear model)은 유지한 체, shrinkage models를 활용해 예측 정확도를 향상하시오.    
       - Lasso, Ridge, 그리고 Elasticnet 3가지 알고리즘 적용 후 예측 성능을 비교, 각 알고리즘의 장단점 설명    
       - scikit-learn 라이브러리에서 아래 모듈을 활용    
         . https://scikit-learn.org/stable/modules/classes.html#module-sklearn.linear_model    
