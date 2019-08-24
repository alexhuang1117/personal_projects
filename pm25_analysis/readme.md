
# Beijing Pollution and Weather Anomaly Detection using LSTM
 
This is a project I am working on during my free time applying some of the techniques I learned working at my current job as a data scientist. The goal of this project is to take the publically available Beijing weather data from 2010 to 2015 and apply anomaly detection techniques to see if we can discover weather and pollution extreme events without any labels. We can later verify the quality and performance of the model by investigating the time period that the model labels as anomalies. Similar techniques can be applied to other time series dataset.

## Data

I am using the Beijing weather and pollution data found [UCI Machine Learning Repo](https://archive.ics.uci.edu/ml/datasets/PM2.5+Data+of+Five+Chinese+Cities). The dataset contains the following features:
* year: year of data in this row 
* month: month of data in this row 
* day: day of data in this row 
* hour: hour of data in this row 
* season: season of data in this row 
* PM: PM2.5 concentration (ug/m^3) 
* DEWP: Dew Point (Celsius Degree) 
* TEMP: Temperature (Celsius Degree) 
* HUMI: Humidity (%) 
* PRES: Pressure (hPa) 
* cbwd: Combined wind direction 
* Iws: Cumulated wind speed (m/s) 
* precipitation: hourly precipitation (mm) 
* Iprec: Cumulated precipitation (mm)

## Model

I am building two models, one for catching anomalies in the weather in general, one for catching anomalies in the pollution specifically. 

## Results

### General Weather 
![result weather](image/weather_train.png)

### Pollution 
![result pollution](image/pollution_train.png)

## Future Work
