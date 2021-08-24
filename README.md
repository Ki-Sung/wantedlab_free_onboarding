## Week2
### 1. 데이터 분석 수업: "Machine Learning 기초"
- 수업일자: 2021년 08월 07일 (토요일) 09시 00분 ~ 14시 00분 / 2021년 08월 08일 (일요일) 09시 00분 ~ 13시 00분
- 수업파일: **'Week2_Class 폴더'**
- 수업내용 및 파일 
  - 실전예제 1: **'Linear_Regression으로_키_몸무게_예측해보기.ipynb'**
  - 실전예제 2: **'Regression으로_보스턴_부동산_가격_예측해보기_(EDA_&_Feature_Selection).ipynb'**
  - 실전예제 3: **'5강_실전예제2_대형마트_상품판매량_예측하기.ipynb'**
### 2. Week2 두 번째 프로젝트
- 주제: Jobis & Villains에서 제공한 데이터로 **1)고객의 결제여부에 영향을 미치는 요인이 무엇인가?**, **2)고객의 수수료 결제금액의 합을 높이기 위해서 어떻게 해야 하는가?** 의 2가지 목표로 프로젝트 진행
- 데이터 출처: 자비스앤빌런스에서 제공한 **'jobis_3o3.csv'**
- 프로젝트 파일: **'team2_week2_analysis.ipynb'**
- 프로젝트 발표일: 2021.08.14
- 발표자: 정상현
- 팀원  
  - **유현준 (팀장)**: 데이터 파악 후 EDA, 전체 Feature간 상관관계 파악, 고객 결제 여부에 따른 특성 비교, 결제여부를 위한 결제비율 지표 산출  
  - **김기성**: 데이터 파악 후 EDA, 자비스앤빌런스 기업조사, 소득 년도별 소득건수와 수수료 결제비율 비교 분석, 상관관계가 있는 Feature들을 위주로 Regression modeling 시도 
  - **정상현**: 데이터 파악 후 EDA, XGB 분류 모델 사용, income 사업 변수 및 소득 데이터 분석, 나이별 데이터로 비교 분석, 두 번쨰 프로젝트 최종 발표 
  - **최창효**: 데이터 파악 후 EDA, 결제여부 기준으로 고객 분류, income 사업 변수 및 소득 데이터 분석
- 사용한 언어: [![Python Badge](http://img.shields.io/badge/-Python%20-blue?style=flat-square&&logoColor=yellow&logo=python&link=https://www.python.org/)](https://www.python.org/) [![Numpy Badge](http://img.shields.io/badge/-Numpy%20-013243?style=flat-square&&logoColor=white&logo=numpy&link=https://numpy.org/)](https://numpy.org/) [![Pandas Badge](http://img.shields.io/badge/-Pandas%20-150458?style=flat-square&logoColor=white&logo=pandas&link=https://pandas.pydata.org/)](https://pandas.pydata.org/) [![Matplotlib Badge](http://img.shields.io/badge/-Matplotlib%20-2350A9?style=flat-square&logoColor=white&logo=matplotlib&link=https://matplotlib.org/)](https://matplotlib.org/) [![Seaborn Badge](http://img.shields.io/badge/-Seaborn%20-212E50?style=flat-square&logoColor=white&logo=seaborn&link=https://seaborn.pydata.org/)](https://seaborn.pydata.org/) [![Sklearn Badge](http://img.shields.io/badge/-Sklearn%20-F7931E?style=flat-square&logoColor=black&logo=scikit-learn&link=https://scikit-learn.org/stable/)](https://scikit-learn.org/stable/)
### 프로젝트 과정
1. EDA - 각 컬럼 파악 
2. 고객 결제여부에 영향을 미치는 요인과 총 결제금액 합의 개선을 위한 분석 
3. Income 사업 변수 및 소득 데이터 분석 
4. AGE 변수 분석 
5. Refund 변수 분석 
6. Year 변수 분석과 결제금액 총합계 증대방안
### 프로젝트 결과
1. EDA 분석 결과 결제여부는 약한 상관관계가 있는 사업소득 유무를 제외하면, 상관관계가 있는 변수는 없는 것으로 판단, 단 결제금액을 보면 상식적으로 생각하는 것처럼 사업소득, 기타소득, 환급액과 수수료에 상관관계가 존재함을 확인
2. 머신러닝 분류 (XGB 분류) 모델을 통해 지불여부에 대해 데이터 학습하고 feature importance한 결과 여기서 가장 중요한 feature는 사업소득, 나이, 근로소득, 환급액, 기타 소득으로 결과 도출 
3. 최종결과 2020년에 총 결제율과 결제데이터의 수는 크게 하락하였으나 결제금액의 평균값과 총합계가 급증하였고, 2020년에 사업소득이 2,793,000에서 39,934,000 범위(최상위)에 해당하는 고객은 다른해에 비해 약 2.9배 증가하였다.
4. 사업소득 최상위 그룹은 26세 이상 고객의 비율이 다른 사업소득 그룹보다 높고, 남성의 비율이 다른 사업소득 그룹보다 높다, 이 기준에 해당하는 고객이 가장 많이 쓰는 플랫폼에서 해당 그룹을 타게팅하여 마케팅할 경우 결제 금액 총합계의 증대를 예상할 수 있다. (전체 데이터에서도 26세에서 29세사이가 결제금액의 합이 제일 높다.)
### 아이디어 제시 
- 환급액의 2주에서 4주후에 지급된다. 그런데 토스에서 주식을 판 돈을 단기 대출의 개념으로 소정의 이자로 바로 쓸 수 있다. 프리랜서들의 경우 급전이 필요한 경우가 많고, 심리학적으로 금액에 큰 차이가 없다면 대체로 사람들은 돈을 바로 받는 경우를 선호한다. 그러므로, 환급금을 자비스앤빌런즈에서 바로 입금하고 소정의 이자를 결제 창 전에 선택하여 수수료에 추가하는 방향으로 서비스를 추가하면 총 결제 금액의 합을 증대시키는데 도움이 될 것이다. 이때 수수료는 환급금액을 기준으로 고액은 몇 %로 표기하는 것이 심리적 부담이 적을 것이고, 천원 단위 이하의 수수료는 **"2000원만 추가하시면 바로 환급금을 받으실 수 있습니다. 받으시겠습니까?"** 등으로 금액으로 표기하기 하는 것이 결제유도에도 도움이 될 것으로 생각한다. 이때 금액을 설정하면서 AB테스트를 활용하여 조정할 필요가 있다.

#### [Week2 Project의 자세한 내용과 코드는 여기를 클릭](https://nbviewer.jupyter.org/github/Ki-Sung/wantedlab_free_onboarding/blob/main/team2_week2_analysis.ipynb)
