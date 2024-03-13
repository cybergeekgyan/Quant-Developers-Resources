## ARIMA + GARCH Trading Strategy on Stock Market Using Python and R

ARIMA + GARCH time series models to a predictive trading strategy applied to the:
   - S&P 500 US Stock Market Index
   - Nifty50 Index

### Strategy Overview

The strategy is carried out on a "rolling" basis:

1. for each day, n, the previous k days of the differenced logarithmic returns of a stock market index are used as a window for fitting an optimal ARIMA and GARCH models.
2. The combined model is used to make a prediction for the next days returns;
   - If the prediction is -ve: the stock is shorted at the previous close,
   - If the prediction is +ve: the stock is longed
   - If the prediction is same direction as the previous day: then nothing is changed
