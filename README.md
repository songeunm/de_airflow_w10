# de_airflow_w10
### DAG 작성 실습

<ol>songeun_w10_CountryInfo.py</ol> <br>
api를 통해 아래의 정보를 읽어와 Redshift에 테이블을 생성하고 적재하는 DAG <br>
Full Refresh <br>
UTC로 매주 토요일 오전 6시 30분에 실행되도록 스케줄링 <br>
<br>
country: 국가명<br>
population: 인구수<br>
area: 국토 면적<br>

<br><br>

<ol>songeun_w10_OpenWeather.py</ol> <br>
api를 통해 아래의 정보를 읽어와 Redshift에 테이블을 생성하고 적재하는 DAG <br>
Full Refresh <br>

<br>
date: 날짜<br>
temp: 낮 기온<br>
min_temp: 최저 기온<br>
max_temp: 최고 기온<br>
created_date: 생성 날짜(api X)<br>

<br><br>
