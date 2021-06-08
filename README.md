# Time Series Forecast on the AQI in Shanghai
## Background Introduction
Predicted the Air Quality Index in Shanghai using the temperature features contains three years' daily records by SAS. 

## Analysis Process
- Aggregated new column that reflects outliers from the original dataset and converted them into dummy variables.
- Applied Univariate (Seasonal Dummies, Cyclical Trend, ARIMA) and Multivariate (Regression, Error Model, Cross Correlation) time series models on the updated dataset.
- Compared fits of the model with the highest estimate variance.
- Selected the model with the best predictive performance that possesses the lowest MAPE on the validation set.

## Software Used
- SAS
- Excel

