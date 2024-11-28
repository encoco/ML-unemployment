<div align="center">

SARIMA,ARIMA를 이용한 미래 청년 실업률 예측
<img src="https://img.shields.io/badge/프로젝트 기간-2024.07~2024.11-green?style=flat&logoColor=white" />
</div>

## 📝 소개
과거 청년 실업률,GDP,최저임금,청년인구, 경제활동인구의 데이터를 활용하여 미래의 실업률을 예측하는 모델이다.

경제활동인구 데이터에 있는 최종학력과 실업률, 경제활용참가율을 토대로 ARIMA 모델을 개발했고
GDP,최저임금,청년인구를 외부 변수로 두고 청년 실업률을 이용한 SARIMA 모델을 구현했다.

## 시각화
#### 교육수준별 실업률 
![교육수준별_실업률_시각화](https://github.com/user-attachments/assets/3fd00def-efea-428a-a1d4-ef5bda036071)

#### ARIMA를 이용한 예측
![미래실업률예측](https://github.com/user-attachments/assets/422267f7-eb9e-46e0-8e56-e29bc4baf506)

#### SARIMA를 이용한 예측
![SARIMA 예측](https://github.com/user-attachments/assets/324d5a7d-9607-4e75-b670-21110b8deaf1)

## 주요 특징
![image](https://github.com/user-attachments/assets/6e680907-1ee4-465d-9f41-79769bbb33b8)


<br/>
![sarima_로그](https://github.com/user-attachments/assets/b91e621f-e09f-477a-88b9-a51f49800d19)

- GDP, 청년인구, 최저임금 데이터를 표준화하고 로그변환하여 전처리
- ARIMA 모델에 계절성과 외부요인(GDP, 청년인구, 최저임금)을 추가한 SARIMAX 모델 사용



## ⚙ 기술 스택
## Development Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

#### Data Processing
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

#### Machine Learning & Statistical Analysis
![Scikit-learn](https://img.shields.io/badge/Scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-2196F3?style=for-the-badge&logo=python&logoColor=white)

#### Visualization
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-385F73?style=for-the-badge&logo=python&logoColor=white)

#### Version Control
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
