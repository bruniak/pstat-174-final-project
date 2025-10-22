# pstat-174-final-project
Time Series Analysis of Hospitality Employment in California

The hospitality industry is a big driver of America’s GDP, generating upwards of 500 billion dollars per year.
In this forecasting project, we are interested in forecasting the number of employees in the hospitality/service
industry. This is important because the low (and high) points can serve as markers for how the economy is
doing, which is really helpful.
 
We selected a SARIMA(2,1,2)×(0,1,1)12
model to forecast the number of employees in the service industry. After looking at 4 potential models, this
one came out on top. By comparing the forecasted values with the actual values, we found that the model
fit the test set pretty well, with a slight overestimation of the employee count. The gap increased as time
progressed. The data pertaining to this project documents the change in employees in the hospitality service industry in
California from 1990-01-01 to 2018-12-01. Specifically, it looks at the monthly average employed in thousands
of persons. It is a seasonal time series dataset
