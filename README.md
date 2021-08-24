# Wantedlab Free on Baording Pre_project
- 데이터 출처: **wantedlab**에서 제공한 **'stock.adj_close.csv'**
- 제출일: 2021.07.29
- 작성자: [김기성](https://github.com/Ki-Sung)
- 컬럼명
  - symbol: 주식 종목코드 (발행체 고유코드)
  - 2018-06-01 ~ 2020-09-18: 일별 종목 주식 가격 (종가 기준)
  - row: 2,274개, columns: 569개
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

#### [Pre Project의 자세한 내용과 코드는 여기를 클릭](https://nbviewer.jupyter.org/github/Ki-Sung/wantedlab_free_onboarding/blob/main/pre_project.ipynb)
