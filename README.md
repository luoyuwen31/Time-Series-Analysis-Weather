# Time Series Forecast on the AQI in Shanghai
## Background Introduction
Predicted the Air Quality Index in Shanghai using the temperature features contains three years' daily records by SAS. 

## Dataset Discription
1. Data Source (https://www.kaggle.com/erhankul/shanghai-air-pollution-and-wheather-20142021)
2. We update the dataset contains about three years' daily records from 01/01/2018 to 01/25/2021.
3. Variables information:
- PM 2.5
- PM10
- Ozone (O3)
- Nitrogen dioxide (NO2)
- Sulfur Dioxide (SO2)
- Carbon Monoxide (CO)
- Air Quality Index and Effects on Human Health

## Methodology
1. Aggregated new column that reflects outliers from the original dataset and converted them into dummy variables.
2. Applied Univariate (Seasonal Dummies, Cyclical Trend, ARIMA) and Multivariate (Regression, Error Model, Cross Correlation) time series models on the updated dataset.
3. Compared fits of the model with the highest estimate variance.
4. Selected the model with the best predictive performance that possesses the lowest MAPE on the validation set.

## Software Used
- SAS
- Excel

