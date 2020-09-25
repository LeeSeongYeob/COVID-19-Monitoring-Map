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
![map](https://user-images.githubusercontent.com/59818703/94287454-49b28b00-ff91-11ea-8f61-f8924a008b4c.jpg)

## COVID-19 누적 데이터 그래프

### Data

- 누적 데이터 [https://livecorona.co.kr/](https://livecorona.co.kr/)

preprocessing  → JSON data to DataFrame

### Using Libaray

- pandas
- plotly

### Result

- data format : HTML file, Image (PNG,JPG..etc)

![graph](https://user-images.githubusercontent.com/59818703/94287495-5931d400-ff91-11ea-8ae4-1ecd4a681b02.jpg)
