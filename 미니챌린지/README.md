https://www.kaggle.com/competitions/sejonguniai-12312312


# 프로젝트
공공데이터를 활용하여 사회적문제를 해결하는 것을 목표로 합니다.


복수의 공공데이터를 직접 가공하여 사용하였습니다.


Kaggle Competition을 직접 제작하였습니다.


# 주제
기상청의 기상 데이터를 바탕으로 풍력발전소의 일평균 발전량을 예측하는 문제입니다.


# 데이터
사용한 공공데이터의 출처입니다

한국남부발전(주)_성산풍력발전실적
https://www.data.go.kr/data/15043393/fileData.do


한국남부발전(주)_성산풍력 일평균 풍속데이터
https://www.data.go.kr/data/15076400/fileData.do


[기상청 기상자료개방포털] 종관기상관측(ASOS)
https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pgmNo=36


TrainData.csv = 18년 1월 1일 부터 12월 31일 까지의 기상 데이터와 일별 평균 풍력발전 실적을 포함하고 있습니다.


TestData.csv = 18년도의 임의의 날짜 7개를 선택해 일별 평균 풍력발실적을 뺀 값입니다. train 데이터에는 해당 날짜가 없습니다.


submit.csv = 제출양식 TARGET 값(일평균 풍력발전 실적 예측 값)을 채워주세요


# Columns
'ID' - 년일월의 정보를 가지고 있습니다


평균기온, 일강수량, 순간 풍속등의 정보는 기상청의 공공 데이터이고 풍향의 값은 각도를 나타내고 있습니다.


'성산1호기(초 당 m)' 은 한국남부발전의 공공 데이터인 성산 1호기 풍력발전기의 일평균 풍속 데이터입니다


'평균' 은 일평균 풍력발전 실적 데이터입니
