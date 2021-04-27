# Database_and_Analytics_Programming_Project
(The repository for the Database &amp; Analytics Programming continuous assessment group project.)

A project to visualise & correlate the spread and socio-economic impact of **COVID-19** across the planet using dataframes and visualisations in Python. <br>

### Libraries/Packages used:
- numpy
- pandas
- matplotlib
- seaborn
- geopandas
- selenium
- bs4 (BeautifulSoup)
- mpl_toolkits
- shapely
- requests
- json
- psycopg2
- urllib

### Installation (On Google Colab):
    !pip install --upgrade geopandas
    !pip install selenium
    !pip install beautifulsoup4
    !pip install --upgrade pyshp
    !pip install --upgrade shapely
    !pip install --upgrade descartes
    !pip install psycopg2

### Data Acquisition:
#### For COVID-19 World Maps:
- [CovidAPI Postman link](https://documenter.getpostman.com/view/2568274/SzS8rjbe?version=latest)
- [backtrackbaba/covid-api on GitHub](https://github.com/backtrackbaba/covid-api)

According to the GitHub documentation, the API uses data from:
- [Novel Coronavirus (COVID-19) Cases, provided by JHU CSSE](https://github.com/CSSEGISandData/COVID-19)
- [JSON time-series of coronavirus cases (confirmed, deaths and recovered) per country - updated daily](https://github.com/pomber/covid19)

#### For Stock Market data:
- Web scraping the [Yahoo Finance webpage](https://finance.yahoo.com/) using _Beautiful Soup_.
- [Beautiful Soup Documentation](https://pypi.org/project/beautifulsoup4/)


### Sample Images produced:
![2020-01-22](/final_images/dashboard/COMBO_1.png)
![2020-02-20](/final_images/dashboard/COMBO_2.png)
![2020-03-20](/final_images/dashboard/COMBO_3.png)
![2020-04-13](/final_images/dashboard/COMBO_4.png)

![Video showcasing the dashboard](/final_videos/0.25sec_each_VIDEO.mp4)


### Report:
The final report that was submitted for the DAP project can be viewed/downloaded from [this link](https://github.com/singhad/Database_and_Analytics_Programming_Project/raw/master/%23Report/DAP_Report.pdf).




