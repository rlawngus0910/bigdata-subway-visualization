# bigdata-subway-visualization

### 서울시 지하철 정보 시각화 프로젝트

- 서울시 지하철 승객 수와 코로나-19 사태의 상관관계를 분석 및 시각화
- 호선별 승객수, 역별 승객수 시각화 (2021년 4월 기준)
- 서울시 지하철 승객 수와 출퇴근 시간의 상관관계를 분석 및 시각화



### 팀명 및 팀원

- 팀명 : KJH
- 팀원 : [김주현](https://github.com/rlawngus0910), [최종헌](https://github.com/ChoiJongheon), [조환철](https://github.com/JoHwanCheol)



### 기술스택

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"><img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=PyCharm&logoColor=white"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white"><img src="https://img.shields.io/badge/GoogleColab-F9AB00?style=for-the-badge&logo=GoogleColab&logoColor=white"><img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">



### DataSet

- [서울시 지하철 호선별 역별 시간대별 승하차 인원 정보](http://data.seoul.go.kr/dataList/OA-12252/S/1/datasetView.do)
- [서울시 코로나19 확진자 현황](http://data.seoul.go.kr/dataList/OA-20279/S/1/datasetView.do)
- [서울 지하철역 좌표](https://observablehq.com/@taekie/seoul_subway_station_coordinate)



### Visualization

1. 지하철 호선별 승객 수 시각화 - Bar Chart

   ![readme캡처1](https://user-images.githubusercontent.com/57345435/122038780-ed3e1700-ce10-11eb-873b-e63d926f420e.PNG)

2. 지하철 역별 승객 수 시각화 - Hitmap

   ![readme캡처2](https://user-images.githubusercontent.com/57345435/122038846-fd55f680-ce10-11eb-887e-743c3a876062.PNG)

3. 출퇴근 시간 동안 가장 승객 수가 많은 역 시각화 (20위까지) - Bar Chart

   ![readme캡처3](https://user-images.githubusercontent.com/57345435/122038869-05ae3180-ce11-11eb-9e38-6b99bdfb5e27.PNG)

   **06시~09시에 승차 인원이 가장 많은 역과 19시~22시에 하차 인원이 가장 많은 역이 동일하고 (신림), 07시~10시에 하차 인원이 가장 많은 역과 18시~21시에 승차 인원이 가장 많은 역이 동일한 것을 볼 수 있다. (가산디지털단지)**

   

4. 월별 코로나-19 확진자 수와 월별 지하철 탑승객 수 시각화 - Bar Chart, Line Chart

   (1) 월별 코로나 확진자 수 (2020년 기준)

   ![readme캡처4](https://user-images.githubusercontent.com/57345435/122038890-09da4f00-ce11-11eb-87f1-e6a33764a02b.PNG)

   (2) 월별 지하철 탑승객 수

   ![readme캡처4-1](https://user-images.githubusercontent.com/57345435/122038904-0cd53f80-ce11-11eb-90e5-52d684338586.PNG)

   **코로나 대유행 시기와 지하철 탑승객 수는 거의 반비례하는 것을 알 수 있다.**

   

5. 2019년과 2020년의 지하철 호선별 탑승객 수 비교

   ![readme캡처5](https://user-images.githubusercontent.com/57345435/122038915-11015d00-ce11-11eb-83b0-0b578b2d44e6.PNG)

   **코로나 사태 전후를 비교했을 때 코로나 이전의 탑승객 수가 더 많은 것을 알 수 있다.**

