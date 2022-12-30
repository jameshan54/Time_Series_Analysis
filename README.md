# Time_Series_Analysis
Car Sales Analysis using Time Series

The dataset includes a total of 120 observations from January 2007 to December 2016. I was always wondering when the best time is to buy a new car and this dataset caught my attention. My goal in this project is
to predict car sales, however, considering the lack of observation, I used 12 observations of 2016 as a testset
to validate the prediction.
In order to predict car sales, I used time series techniques including box-cox transformation, comparing
acfs/pacfs, differencing, AICc computation, and diagnosis checking. After doing all the model transformations, I compared three different models out of 11 possible models, and chose one model that had the best
result in diagnosis checking. All 11 possible models had low p-values for Shapiro-test so the model that had
the highest p-value of 0.04635 and passed all the diagnostic tests were chosen. Differencing at different lags
or applying different values of lambda for Box-Cox transformation didn’t improve the model performance.
Both predictions of transformed data and original data were within the confidence interval. However, the
prediction was almost linear and was not best at giving meaningful insight but having more data would have
possibly given better insights.
The dataset was collected from Kaggle, https://www.kaggle.com/datasets/dmi3kno/newcarsalesnorway and
R was used throughout the project
