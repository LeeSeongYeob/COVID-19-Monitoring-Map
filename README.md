# COVID-19-Monitoring-Map

## COVID-19 시,도별 확진자, 사망자

### Data

- 시,도별 한국 data [http://api.corona-19.kr/](http://api.corona-19.kr/korea/country)
- 대한민국 행정구역 geo data (JSON)
    - [https://github.com/southkorea/southkorea-maps](https://github.com/southkorea/southkorea-maps)

### Using Library

- pandas
- json
- geopandas
- requests
- re
- folium

### Result

- data format : HTML file

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1bc6633a-a66a-4349-85ab-f93f6fde9c72/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1bc6633a-a66a-4349-85ab-f93f6fde9c72/Untitled.png)

## COVID-19 누적 데이터 그래프

### Data

- 누적 데이터 [https://livecorona.co.kr/](https://livecorona.co.kr/)

preprocessing  → JSON data to DataFrame

### Using Libaray

- pandas
- plotly

### Result

- data format : HTML file, Image (PNG,JPG..etc)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1db24505-8da6-4aed-b407-eec91a354036/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1db24505-8da6-4aed-b407-eec91a354036/Untitled.png)
