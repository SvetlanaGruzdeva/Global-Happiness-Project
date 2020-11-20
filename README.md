# Global Happiness Project
![image](./img/image.jpg)

### Motivation
This project has been inspired by well known fact that there is a strong correlation between climate and suicide ratio around the world. The idea of the project is to check if there is 
a similar correlation with happiness ratio using data for the period 2015-2018.

### Overview
Raw data has been downloaded from various sources in csv format and then stored in SQL database.<br/>
Cleaning and analysis has been performed by Python and Tableau

### Report
Presentation prepared in Tableau Public https://public.tableau.com/profile/svetlana.gruzdeva#!/vizhome/Happiness_Project_16057811399910/start<br/>

### Software used
SQL database (MySQL)<br/>
Jupyter Notebook<br/>
Tableau

### Programmic language
Python 3.8.3

### Libraries used
- os
- re
- math
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sqlalchemy
- pymysql
- requests
- bs4
- sklearn.linear_model
- statsmodels.tsa.ar_model
- scipy import stats

### Sources
World Happiness Report - https://www.kaggle.com/unsdsn/world-happiness<br/>
Suicide Rates Overview - https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016<br/>
Suicide Rates Overview (2015-2016) - https://data.worldbank.org/indicator/SH.STA.SUIC.P5?view=map<br/>
Suicide Rates Overview (2017-2018) - https://data.oecd.org/healthstat/suicide-rates.htm<br/>
Average Temperature by Country - https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data?select=GlobalLandTemperaturesByCountry.csv<br/>

### Assumptions and estimations
General assumption has been made that collected data is reliable and representative.<br/>
Average annual temperature available in data set didn't contain reqiured period so linear regression model has been used to extrapolate available data to required period.