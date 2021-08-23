# wantedlab Free on Baording Data Analysis Class
<img src="https://user-images.githubusercontent.com/80456601/128636455-a3d15a89-d8f1-4363-94f1-ac9a3e9e9188.png" width="80%" height="50%"/>

### - 과정소개 
#### 일시: 2021년 07월 31일 ~ 2021년 08월 27일
1. Pre Project 제출 후 선발
2. Week1 수업 및 첫 번째 프로젝트
3. Week2 수업 및 두 번쨰 프로젝트
4. Week3 수업 및 세 번째 프로젝트
5. Week4 채용설명회 및 수료식
---
## 1. Pre Project 
### 주제: 주가 데이터로 가설을 설정하고 분석하기 
- 데이터 출처: **wantedlab**에서 제공한 **'주가 데이터'**
- 프로젝트 파일: **'pre_project.ipynb'**
- 작성자: [김기성](https://github.com/Ki-Sung)
- 프로젝트 자세한 내용: [pre_project_branch](https://github.com/Ki-Sung/wantedlab_free_onboarding/tree/pre_project)
- 사용한 언어: [![Python Badge](http://img.shields.io/badge/-Python%20-blue?style=flat-square&&logoColor=yellow&logo=python&link=https://www.python.org/)](https://www.python.org/) [![Numpy Badge](http://img.shields.io/badge/-Numpy%20-013243?style=flat-square&&logoColor=white&logo=numpy&link=https://numpy.org/)](https://numpy.org/) [![Pandas Badge](http://img.shields.io/badge/-Pandas%20-150458?style=flat-square&logoColor=white&logo=pandas&link=https://pandas.pydata.org/)](https://pandas.pydata.org/) [![Matplotlib Badge](http://img.shields.io/badge/-Matplotlib%20-2350A9?style=flat-square&logoColor=white&logo=matplotlib&link=https://matplotlib.org/)](https://matplotlib.org/) [![Seaborn Badge](http://img.shields.io/badge/-Seaborn%20-212E50?style=flat-square&logoColor=white&logo=seaborn&link=https://seaborn.pydata.org/)](https://seaborn.pydata.org/) 
### 프로젝트 과정 
1. 각 컬럼의 의미 파악 - 데이터 조사 
2. 데이터 분석 - EDA 
3. 대표적으로 2개의 종목을 분석 (A000020 종목과 A000030 종목을 분석)
### 프로젝트 결과 
1. **A00002**은 **'동화약품'** 종목이며, 종가 기준으로 가장 낮은 가격은 **2020-03-20 일자 4,985** / 가장 높은 가격은 **2020-08-14 일자 30,300** 이었다.
2. 낮은 가격일자를 기준으로 공시 및 뉴스를 찾아보니 3월 16일 기준 3일전날의 종가보다 **15%이상 하락**하여 **투자주의종목으로 지정**(코로나 19 사태가 커지면서 주식이 급락한 것 으로 예상) 되었으며, 2020년 4월 24일 주가가 급등하여 또 한번 투자주의 종목으로 지정되었다.
3. 그리고 2020년 8월 19일자 뉴스에서 **코로나19 치료제 2상 임상시험 신청**과, 동물효능시험에 의해**유의미한 바이러스 억제 효능이 관찰 되었다는 뉴스가 보도**, 주가는 다시 급등하게 되었다.
4. **A000030**은 **구 우리은행** 종목이며, 종가 기준으로 **가장 낮은 가격은 2019-01-07 일자 14,550** / **가장 높은가격이 2018-12-23 일자 17,150** 이었다.
5. 해당 종목은 2019년 1월 8일 부로 일정한 가격이 표시, 이는 당시 우리금융지주로 종목 명이 바뀌면서 우리은행이 거래정지 상태였음을 확인하였다. 
6. 우리금융지주로 종목명이 바뀌면서 해당 종목인 **A316140**를 추가로 분석 상장하자마자 주가가 떨어지는 모습이 보여졌다. 동화약품 때와 비슷하게 3월 중순 코로나 19 사태로 주가가 최저점을 찍었다. 
### 프로젝트 개선점 
1. 각 종목별로 하나하나씩 데이터를 가져와서 보는 것이 불편함. 코드로 정리가 필요.
2. 자료들을 찾는 과정이 쉽지 않음, 데이터에 맞게 정보를 얻는 방법이 아직은 부족, 공부가 더 필요(해당 과정을 신청하게 된 이유).
3. 다양한 시각화 툴 사용 필요.
4. 가설을 설정하지 않고, 바로 EDA 진행, 충분한 가설 설정이 필요.
---
## 2. Week1 
### 2-1. 데이터 분석 수업: "프로그래밍과 파이썬 기본 문법"
- 수업일자: 2021년 07월 31일 (토요일) 09시 00분 ~ 14시 00분 / 2021년 08월 01일 (일요일) 09시 00분 ~ 13시 00분
- 수업파일: **'Week1_Class 폴더'**
- 수업내용 및 파일 
  - python 기초: **'1강_python_기초예제_matplotlib.ipynb'**
  - python 패키지 기초: **'2강_쉽게_사용하는_데이터_분석_공구세트_pandas와_numpy.ipynb'**
### 2-2. Week1 첫 번째 프로젝트
- 주제: 원티드 국민연금 DataBase를 이용해서 유니콘 기업 발굴하기 
- 데이터 출처: 원티드에서 제공한 **'company_nps_data.csv'**
- 프로젝트 파일: **'team2_week1_analysis.ipynb'**
- 프로젝트 발표일: 2021.08.07
- 발표자: 유현준(Team2 팀장)
- 팀원  
  - **유현준 (팀장)**: 데이터 파악 후 EDA, 팀원들의 모든 EDA 결과 취합, 첫 번째 프로젝트 최종 발표  
  - **김기성**: 데이터 파악 후 EDA, 현 유니콘 기업 매출과 직원수 조사, 유니콘 기업 5개 선정
  - **김한빈**: 데이터 파악 후 EDA, EDA 방향 설정
  - **맹광국**: 데이터 파악 후 EDA, 국민연금 세금 계산 기준 조사
  - **박선하**: 데이터 파악 후 EDA, 정규분포를 보이는 컬럼을 스케일링하여 스코어화 구현
  - **정상현**: 데이터 파악 후 EDA, ML 모델링으로 가능한지 파악 
  - **정서현**: 데이터 파악 후 EDA, 성장률 기준 Top10 기업 산출 
  - **최창효**: 데이터 파악 후 EDA, 1인당 매출액과 1인당 연금보혐료를 활용한 점수 계산  
  - **최현숙**: 데이터 파악 후 EDA, 기업 2년이상 유지된 곳, 최소 직원수 40명 이상 기준으로 유니콘 기업 선정
- 자세한 내용: [week1 Branch README](https://github.com/Ki-Sung/wantedlab_free_onboarding/blob/week1/README.md)
- 사용한 언어: [![Python Badge](http://img.shields.io/badge/-Python%20-blue?style=flat-square&&logoColor=yellow&logo=python&link=https://www.python.org/)](https://www.python.org/) [![Numpy Badge](http://img.shields.io/badge/-Numpy%20-013243?style=flat-square&&logoColor=white&logo=numpy&link=https://numpy.org/)](https://numpy.org/) [![Pandas Badge](http://img.shields.io/badge/-Pandas%20-150458?style=flat-square&logoColor=white&logo=pandas&link=https://pandas.pydata.org/)](https://pandas.pydata.org/) [![Matplotlib Badge](http://img.shields.io/badge/-Matplotlib%20-2350A9?style=flat-square&logoColor=white&logo=matplotlib&link=https://matplotlib.org/)](https://matplotlib.org/) [![Seaborn Badge](http://img.shields.io/badge/-Seaborn%20-212E50?style=flat-square&logoColor=white&logo=seaborn&link=https://seaborn.pydata.org/)](https://seaborn.pydata.org/) 
### 프로젝트 과정
1. DB구조 파악 및 Column별 검토
2. 분석에 필요한 Column 추가 및 데이터 전처리 
3. 가설 설정 및 검증 
  - 3-1. 가설 설정
    1) 유니콘으로 기대되는 기업은 높은 '성장성'을 나타내는 기업일 것이다.
    2) 유니콘으로 기대되는 기업은 '인적자원'을 중시하는 기업일 것이다.
  - 3-2. 가설 검증 
    1) '성장성'관련 지표: 연매출액 -> 3개의 세부지표 산출 및 점수 계산
    2) '인적자원'관련 지표: 월별 직원수, 인당 평균 연금보혐료
4. 유니콘 기업 최종 선정 
### 프로젝트 결과
1. 유니콘 기업인지 여부를 판단하기 위한 기준을 3년으로 설정 (연매출액 등 지표에 대한 의미있는 변화추이 파악, 중소벤처기업부에서 선정한 거대신생기업의 평균 업력이 3.7년인 점을 고려)
2. 결론 도출을 위해 **"1) 유니콘으로 기대되는 기업은 높은 '성장성'을 나타내는 기업일 것이다.**, **2) 유니콘으로 기대되는 기업은 '인적자원'을 중시하는 기업일 것이다.** 설정
3. 가설 검증을 위해 첫 번째, 연매출액 점수(CAGR, 매출평균 및 지속성장 여부에 따른 "연매출액 점수") 산출 후 설정, 상위 25개의 회사 ID를 추출 
4. 25개 회사 추출 후, 가설 검증을 위해 두 번째, 월별 직원수 기준(최소 직원수 40명 이상, 현존 유니콘 기업 조사 후 참고) 설정, 10개의 회사 ID 추출  (**137755, 470994, 297175, 405759, 403470, 232218, 132156, 127366, 133493, 404804**)
5. 10개 회사 추출 후, 인당 연금보험료 계산 후 최종 5개 유니콘 기업 선정
6. 최종 5개 유니콘 기업은 **127366, 132156, 232218, 297175, 470994**
---
## 3. Week2
### 3-1. 데이터 분석 수업: "Machine Learning 기초"
- 수업일자: 2021년 08월 07일 (토요일) 09시 00분 ~ 14시 00분 / 2021년 08월 08일 (일요일) 09시 00분 ~ 13시 00분
- 수업파일: **'Week2_Class 폴더'**
- 수업내용 및 파일 
  - 실전예제 1: **'Linear_Regression으로_키_몸무게_예측해보기.ipynb'**
  - 실전예제 2: **'Regression으로_보스턴_부동산_가격_예측해보기_(EDA_&_Feature_Selection)'**
  - 실전예제 3: **'5강_실전예제2_대형마트_상품판매량_예측하기.ipynb'**
### 3-2. Week2 두 번째 프로젝트
- 주제: Jobis & Villains에서 제공한 데이터로 **1)고객의 결제여부에 영향을 미치는 요인이 무엇인가?**, **2)고객의 수수료 결제금액의 합을 높히기 위해서 어떻게 해야 하는가?** 의 2가지 목표로 프로젝트 진행
- 데이터 출처: 자비스앤빌런스에서 제공한 **'jobis_3o3.csv'**
- 프로젝트 파일: **'team2_week2_analysis.ipynb'**
- 프로젝트 발표일: 2021.08.14
- 발표자: 정상현
- 팀원  
  - **유현준 (팀장)**: 데이터 파악 후 EDA, 전체 Feature간 상관관계 파악, 고객 결제 여부에 따른 특성 비교, 결제여부를 위한 결제비율 지표 산출  
  - **김기성**: 데이터 파악 후 EDA, 자비스앤빌런스 기업조사, 소득 년도별 소득건수와 수수료 결제비율 비교 분석, 상관관계가 있는 Feature들을 위주로 Regression modeling 시도 
  - **정상현**: 데이터 파악 후 EDA, XGB 분류 모델 사용, income 사업 변수 및 소득 데이터 분석, 나이별 데이터로 비교 분석, 두 번쨰 프로젝트 최종 발표 
  - **최창효**: 데이터 파악 후 EDA, 결제여부 기준으로 고객 분류, income 사업 변수 및 소득 데이터 분석
- 자세한 내용: [week2 Branch README](https://github.com/Ki-Sung/wantedlab_free_onboarding/blob/week2/README.md)
- 사용한 언어: [![Python Badge](http://img.shields.io/badge/-Python%20-blue?style=flat-square&&logoColor=yellow&logo=python&link=https://www.python.org/)](https://www.python.org/) [![Numpy Badge](http://img.shields.io/badge/-Numpy%20-013243?style=flat-square&&logoColor=white&logo=numpy&link=https://numpy.org/)](https://numpy.org/) [![Pandas Badge](http://img.shields.io/badge/-Pandas%20-150458?style=flat-square&logoColor=white&logo=pandas&link=https://pandas.pydata.org/)](https://pandas.pydata.org/) [![Matplotlib Badge](http://img.shields.io/badge/-Matplotlib%20-2350A9?style=flat-square&logoColor=white&logo=matplotlib&link=https://matplotlib.org/)](https://matplotlib.org/) [![Seaborn Badge](http://img.shields.io/badge/-Seaborn%20-212E50?style=flat-square&logoColor=white&logo=seaborn&link=https://seaborn.pydata.org/)](https://seaborn.pydata.org/) [![Sklearn Badge](http://img.shields.io/badge/-Sklearn%20-F7931E?style=flat-square&logoColor=black&logo=scikit-learn&link=https://scikit-learn.org/stable/)](https://scikit-learn.org/stable/)
### 프로젝트 과정
1. EDA - 각 컬럼 파악 
2. 고객 결제여부에 영향을 미치는 요인과 총 결제금액 합의 개선을 위한 분석 
3. Income 사업 변수 및 소득 데이터 분석 
4. AGE 변수 분석 
5. Refund 변수 분석 
6. Year 변수 분석과 결제금액 총합계 증대방안
### 프로젝트 결과
1. EDA 분석 결과 결제여부는 약한 상관관계가 있는 사업소득 유무를 제외하면, 상관관계가 있는 변수는 없는 것으로 판단, 단 결제금액을 보면 상식적으로 생각하는 것처럼 사업소득, 기타소득, 환급액과 수수료에 상관관계가 존재
2.머신러닝 분류 (XGB 분류) 모델을 통해 지불여부에 대해 데이터 학습하고 feature importance한 결과 여기서 가장 중요한 feature는 사업소득, 나이, 근로소득, 환급액, 기타 소득으로 결과 도출 
