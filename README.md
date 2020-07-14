# 대전시 2020 빅데이터 공모전
"대전시 2020 빅데이터 분석 및 아이디어 공모전"에 참가하며 진행한 프로젝트 입니다.

본 프로젝트는 "대전광역시 행정동별 여성 및 아동 성범죄 위험도 분석"을 주제로 진행하였습니다. 행정동별 접근을 통해 각 지역의 환경과 지역 특색을 고려하여 성범죄 발생 위험도와 그 원인을 다차원적으로 분석하였습니다.

### 사용 데이터
KT 유동인구 데이터(대전시 제공)\
KB카드 업종별 월별 매출액(대전시 제공)\
대전광역시 CCTV 정보 (공공데이터포털)\
대전광역시지방경찰청 대전지역 요일별 시간대별 범죄 발생현황_2017(공공데이터포털)\
동별 면적 (km^2): 각 구별 홈페이지(유성구 : http://www.yuseong.go.kr/ kr/, 동구 : https://www.donggu.go.kr/dg/kor , 대덕구 : http://www.daedeok.go.kr/dpt/DPT.do , 서구 : http://www.seogu.go.kr/kor/main.do , 중구 : http://www.djjunggu.go.kr/html/kr/)\
여성 1인가구 수(주혜진 (2017), 대전지역 여성 1 인가구의 특성과 정책 현안)

## 분석과정

### 데이터 전처리
* 여성 및 아동 유동인구 / 거주인구 :\
성범죄에 주로 노출되는 여성과 10 세 미만 아동에 대한 데이터만 사용\
대전지방경찰청 범죄 현황 데이터를 통해 12-18시 / 21-03시에 강력범죄 발생률이높다 고 파악
