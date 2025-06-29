# 📘 01_Regression: 선형 회귀 및 로지스틱 회귀 실습

회귀 기반 모델에 대한 다양한 실습 예제가 담겨 있습니다.  
단순 선형 회귀부터 로지스틱 회귀까지, 각 기법의 개념과 구현을 단계적으로 학습할 수 있습니다.

## 📄 실습 목록

### ➊ [단순 선형 회귀 (Simple Linear Regression)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/01_Regression/1_1_regression_simple_linear.ipynb)
- 단순선형회귀모형 적합 및 시각화
- `scikit-learn`과 `statsmodels`를 활용한 회귀선 분석
- 예측 및 회귀모형 가정(정규성, 등분산성 등) 확인 실습 포함

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 단순선형회귀 예제  
- 회귀모형 적합 (`LinearRegression`, `ols`)  
- 시각화 (`matplotlib`, `seaborn`)  
- 모델 성능 평가 (MAE, MSE, R²)  
- 새로운 데이터 예측  
- 회귀모형 가정 확인  
- (참고) `statsmodels`로 해석  

</details>


### ➋ [다중 선형 회귀 (Multiple Linear Regression)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/01_Regression/1_2_regression_multiple_linear.ipynb)
- 여러 특성을 사용하는 다중 회귀 모델 비교 및 해석
- `scikit-learn`과 `statsmodels`의 회귀 결과 비교 실습 포함

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 다중 선형 회귀 예제  
- 변수 간 다중공선성 확인 (VIF 분석)  
- 변수 제거를 통한 모델 단순화  
- `LinearRegression`과 `OLS` 회귀 모델 적합  
- R² 및 Adjusted R² 계산  
- 예측 결과 시각화 및 성능 비교  
</details>

### ➌ [범주형 변수 회귀 (Categorical Regression)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/01_Regression/1_3_regression_categorical.ipynb)
- 범주형 변수를 더미 변수로 변환하여 회귀 적용
- 다중공선성 제거 및 모델 비교 실습 포함

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 수치형 데이터 기반 선형 회귀 모델 성능 평가  
- 선택된 범주형 변수에 대해 `pd.get_dummies()`로 원-핫 인코딩 수행  
- 기준 범주 제거를 통한 다중공선성 방지  
- 범주형 포함 여부에 따른 회귀 성능 비교 (R², Adjusted R²)  
</details>

### ➍ [규제 회귀 (Ridge & Lasso Regression)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/01_Regression/1_4_regression_penalized.ipynb)
- Ridge와 Lasso 회귀를 활용한 과적합 방지 및 성능 개선
- 하이퍼파라미터 튜닝과 다양한 모델 성능 지표 비교

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 회귀 예제  
- `LinearRegression`, `Ridge`, `Lasso` 모델 비교  
- GridSearchCV를 통한 alpha 최적값 탐색  
- R², Adjusted R², MAE, MSE, MAPE 등 다양한 성능 지표 계산  
- 테스트 데이터셋에 대한 예측 및 평가  
- 규제 회귀 적용 전/후 모델 성능 비교  
</details>

### ➎ [로지스틱 회귀 (Logistic Regression)](https://colab.research.google.com/github/Dropthe-bit/ai_portfolio/blob/main/01_Regression/1_5_regression_logistic.ipynb)
- 이진 분류 문제를 위한 로지스틱 회귀 분석 실습
- 변수 선택 기법(Sequential Feature Selection)을 활용한 성능 개선

<details>
<summary>📚 포함된 실습 항목 보기</summary>

- 로지스틱 회귀를 이용한 이진 분류  
- 데이터 전처리 및 스케일링  
- 변수 선택 (SFS) 기법을 활용한 피처 최적화  
- 성능 평가 지표 (정확도, 혼동행렬 등) 출력  
- 모델 비교 및 해석  
</details>
