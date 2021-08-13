# wantedlab Free on Baording Week1 First project
- 데이터 출처: **wantedlab**에서 제공한 **'company_nps_data.csv'**
- 기간: 2021.08.01 ~ 2021.08.06
- 발표일: 2021.08.07
- 발표자: 유현준 (팀장)
- 팀원  
  - **유현준 (팀장)**: 데이터 파악 후 EDA, 팀원들의 모든 EDA 결과 취합, 토요일 최종 발표  
  - **김기성**: 데이터 파악 후 EDA, 현 유니콘 기업 매출과 직원수 조사, 유니콘 기업 5개 선정
  - **김한빈**: 데이터 파악 후 EDA, EDA 방향 설정
  - **맹광국**: 데이터 파악 후 EDA, 국민연금 세금 계산 기준 조사
  - **박선하**: 데이터 파악 후 EDA, 정규분포를 보이는 컬럼을 스케일링하여 스코어화 구현
  - **정상현**: 데이터 파악 후 EDA, ML 모델링으로 가능한지 파악 
  - **정서현**: 데이터 파악 후 EDA, 성장률 기준 Top10 기업 산출 
  - **최창효**: 데이터 파악 후 EDA, 1인당 매출액과 1인당 연금보혐료를 활용한 점수 계산 
  - **최현숙**: 데이터 파악 후 EDA, 기업 2년이상 유지된 곳, 최소 직원수 40명 이상 기준으로 유니콘 기업 선정
- 사용한 언어: [![Python Badge](http://img.shields.io/badge/-Python%20-blue?style=flat-square&&logoColor=yellow&logo=python&link=https://www.python.org/)](https://www.python.org/) [![Numpy Badge](http://img.shields.io/badge/-Numpy%20-013243?style=flat-square&&logoColor=white&logo=numpy&link=https://numpy.org/)](https://numpy.org/) [![Pandas Badge](http://img.shields.io/badge/-Pandas%20-150458?style=flat-square&logoColor=white&logo=pandas&link=https://pandas.pydata.org/)](https://pandas.pydata.org/) [![Matplotlib Badge](http://img.shields.io/badge/-Matplotlib%20-2350A9?style=flat-square&logoColor=white&logo=matplotlib&link=https://matplotlib.org/)](https://matplotlib.org/) [![Seaborn Badge](http://img.shields.io/badge/-Seaborn%20-212E50?style=flat-square&logoColor=white&logo=seaborn&link=https://seaborn.pydata.org/)](https://seaborn.pydata.org/) 

## [Team2] 원티드 국민연금 DataBase를 이용해서 유니콘 기업 발굴하기 
### 분석 절차 및 주요 내용 
### 1. DB구조 파악 및 Column별 검토
### 2. 분석에 필요한 Column 추가 및 데이터 전처리 
### 3. 가설 설정 및 검증 
#### 3-1. 가설 설정 
1) 유니콘으로 기대되는 기업은 높은 "**성장성**"을 중시하는 기업일 것이다. [관련 지표: 연매출액(3개년 증감 추이)]
2) 유니콘으로 기대되는 기업은 "**인적자원**"을 중시하는 기업일 것이다. [관련 지표: 월별 직원수, 인당 연금보험료(평균)]
#### 3-2. 가설 검증을 위한 지표 설정 및 지표별 분석: 유니콘 훅보 기업 추출 
1) "**성장성**" 관련 지표 
  - 지표 1. 연매출액 -> 3개의 세부지표 산출 및 점수 계산
    - 세부지표 1. 연평균성장률(CAGR)
    - 세부지표 2. 3개년 지속성장 여부
    - 세부지표 3. 3개년 평균매출 
2) "**인적자원**" 관련 지표
  - 지표 2. 월별 직원수 -> 증감률 기준 후보 기업 추출
  - 지표 3. 인당 연금보험료(평균) -> 증감룰 기준 후보 기업 추출 
### 4. 유니콘 기업 최종 선정
- (첨부) 최종 유니콘 선정 회사 ID별 그래프 추이 확인
