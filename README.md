## Week3
### 1. 데이터 분석 수업: "마케팅 데이터 분석"
- 수업일자: 2021년 08월 14일 (토요일) 09시 00분 ~ 14시 00분 / 2021년 08월 15일 (일요일) 09시 00분 ~ 13시 00분
- 수업파일: **'Week3_Class 폴더'**
- 수업내용 및 파일 
  - 실전예제 1: **'3강_데이터_분석을_통해_나만의_주식_투자전략_만들어보기.ipynb'**
  - 실전예제 2: **'3강_데이터시각화_pandas_plot_실습.ipynb'**
  - 실전예제 3: **'5강_실전예제1_광고캠페인_전환율_및_성과_분석하기.ipynb'**
### 2. Week3 세 번째 프로젝트 <해당 과정에 참여했던 회사 "푸쉬뉴스"와 "페이워크"의 참여 포기로 지난 기수에 진행했던 모두의 주차장 프로젝트로 대체>
- 주제: 모두의 주차장 앱 이용자 별 향후 이용건수 예측 
- 데이터 출처: 모두의 주차장 이용 DB
- 프로젝트 파일: **'team2_week3_01_analysis_for_EDA.ipynb'**, **'team2_week3_01_analysis_for_Modeling.ipynb'**
- 프로젝트 발표일: 2021.08.21
- 발표자: 김기성
- 팀원  
  - **유현준 (팀장)**: 데이터 파악 후 EDA, 모델링에 필요한 Feature 설정, MSE와 MAE 점수 도출
  - **김기성**: 데이터 파악 후 EDA, 모두의 주차장 어플 서비스와 기업조사, 각 컬럼 데이터 EDA, 탐색한 컬럼을 연결하여 분석, 세 번쨰 프로젝트 최종 발표
  - **정상현**: 데이터 파악 후 EDA, XGB 분류 모델 시도, MAE, MSE 점수 도출, Feature importance를 바탕으로 코호트 분석 시도
  - **최창효**: 데이터 파악 후 EDA, 주 데이터와 외부데이터 분석 후 merge, model baseline 설정(날짜와 요일별로 이용량이 달라질 것이다.), MSE, MAE 점수 도출
- 사용한 언어: [![Python Badge](http://img.shields.io/badge/-Python%20-blue?style=flat-square&&logoColor=yellow&logo=python&link=https://www.python.org/)](https://www.python.org/) [![Numpy Badge](http://img.shields.io/badge/-Numpy%20-013243?style=flat-square&&logoColor=white&logo=numpy&link=https://numpy.org/)](https://numpy.org/) [![Pandas Badge](http://img.shields.io/badge/-Pandas%20-150458?style=flat-square&logoColor=white&logo=pandas&link=https://pandas.pydata.org/)](https://pandas.pydata.org/) [![Matplotlib Badge](http://img.shields.io/badge/-Matplotlib%20-2350A9?style=flat-square&logoColor=white&logo=matplotlib&link=https://matplotlib.org/)](https://matplotlib.org/) [![Seaborn Badge](http://img.shields.io/badge/-Seaborn%20-212E50?style=flat-square&logoColor=white&logo=seaborn&link=https://seaborn.pydata.org/)](https://seaborn.pydata.org/) [![Sklearn Badge](http://img.shields.io/badge/-Sklearn%20-F7931E?style=flat-square&logoColor=black&logo=scikit-learn&link=https://scikit-learn.org/stable/)](https://scikit-learn.org/stable/)
### 프로젝트 과정
1. 모두의 주차장 어플과 서비스 소개 
2. 데이터 탐색과 EDA 
3. 모델링 구축 및 검증 
4. 마무리 및 개선점
5. 느낀점
### 프로젝트 결과 
1. 가입일을 살펴본 결과 가입자수는 꾸준히 증가하고 있다.
2. D_TYPE의 정보를 파악해본 결과 USER ID와 1대1로 매칭이 되어 해당 데이터는 User와 관련된 고객 등급이지 않을까 추측 된다.
3. Goods_Type도 파악해본 결과 결제일과 1대N으로 매칭되어 해당 데이터는 주차 이용권 정보로 추측이 된다. 
4. 결제 날짜별 요일별 데이터와 Goods_type에 따라 데이터가 유의미해 보인다.
5. 결제 요일별 Goods_type은 각 타입마다 다르다, A타입은 주말의 사용빈도가 높고, B타입은 금요일의 사용이 높다.
6. LabelEcoding과 OnehotEncoding 후 MSE, MAE 점수가 각각 0.054, 0.083으로 결과가 도출되었다.
### 개선점 과 느낀점
1. 이번 프로젝트 발표가 EDA중심으로 진행이 되었다. 모델링 분석과 코호트 분석이 부재하여 논리적인 분석과 추후 액션플랜이 부재, 이를 보강해야 함.
2. 정확한 모델링 구축에 실패하였다. 모델링에 사용하는 선형회귀, 랜덤포레스트 등 어디에 적용을 해야하는지 사전지식이 부족함, 예측 모델링 분석에 필요한 사항의 공부가 필요.

#### [Week3 Project 발표 PPT는 여기를 클릭](https://docs.google.com/presentation/d/11zSwBGq-5dDLbnmiKh04eTN-oeYg31A0ZNzOL4MeE5U/edit#slide=id.p)
#### [Week3 Project Final EDA 코드는 여기 클릭](https://nbviewer.jupyter.org/github/Ki-Sung/wantedlab_free_onboarding/blob/main/team2_week3_01_analysis_for_EDA.ipynb)
#### [Week3 Project Final Modeling 코드는 여기 클릭](https://nbviewer.jupyter.org/github/Ki-Sung/wantedlab_free_onboarding/blob/main/team2_week3_02_analysis_for_Modeling.ipynb)
