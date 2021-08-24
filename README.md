## Week1 
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

#### [Week1 Project의 자세한 내용과 코드는 여기를 클릭](https://nbviewer.jupyter.org/github/Ki-Sung/wantedlab_free_onboarding/blob/main/team2_week1_analysis.ipynb)
