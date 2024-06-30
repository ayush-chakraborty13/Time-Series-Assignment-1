# Time-Series-Assignment-1
For given time series dataset custom_dataset.csv, answer the following questions.

a. [Excel Submission] Calculate the trend-cycle, seasonality and residuals using MS Excel,
using 2 approaches – (i) classical additive decomposition and, (ii) classical
multiplicative decomposition (note that you should use the window size as 13 for
calculating centered moving average for trend, as data is monthly)
b. [Python Submission] Calculate the results using the seasonal_decompose() method
from statsmodels library in Python.

For the same time series dataset custom_dataset.csv, answer the following questions.
For forecasting, take all data until last 3 periods as train dataset, and last 3 periods as test
dataset.

a. [Excel Submission] Forecast for a time horizon of 3 periods (test dataset) using the 4
simple approaches as discussed in class (Naïve, Historical Average, Drift, Seasonal
Naïve) using MS Excel. Assume classical additive decomposition for adjusting the series
seasonally before forecasting.
b. [Excel Submission] Calculate the test Mean Absolute Percentage Error (MAPE) and test
Mean Absolute Error (MAE) for the forecasted Excel results manually.
c. [Python Submission] Calculate the results using in-built methods for the 4 simple
approaches, using Nixtla framework and also calculate the MAPE and MAE values.


For a time series dataset inflation.csv, answer the following questions. For forecasting,
take all data until last period as train dataset, and last period as test dataset.

a. [Excel Submission] Forecast the time series for a time horizon of 1 period (test dataset)
manually in Excel using the Simple Exponential Smoothing method with an optimal
alpha value.
(The alpha is a parameter of exponential smoothing, and you should find the optimal
alpha value using the training dataset, by using Solver)
b. [Excel Submission] Also, compute the train and test metrics (MAPE and MAE each)
c. [Python Submission] Implement Simple Exponential Smoothing, Holt’s model, HoltWinter’s model and Theta model using Nixtla in Python for the same forecasting objective (as in part a. of this question), and calculate the train and test metrics (MAPE
and MAE each).
