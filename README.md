# final_project
The following is an introduction to the files used in the project.

1.Simulation. Simulate a time series with random walk and trend-stationarity.
I wrote some comments on the test in trend-stationarity.

2.Prediction. Test in 5 datasets: HSI, GDAXI, Crude oil, Apple and Bitcoin.
Because I'm just changing the datasets, I only wrote some comments on the test in Apple. And do some statistical tests on 5 datasets in a separate file.The time required to reconstruct the data 100 times in HSI is given, not including the time of retraining the model.

3.Classification. Test Bitcoin one-minute price series.

4.The final report.

Datasets: the daily data of HSI,GDAXI,Crude oil,Apple and Bitocoin is from yfinance, and the bitcoin one-minute data is compressed and uploaded.

***

Some important module:

1. fathon

* Supported platforms : Linux x86_64,Linux ARM64,macOS x86_64,Windows 64bit

2. PyEMD

* $ pip install EMD-signal

***

The version of the package
* scikit-learn            1.1.1

* TA-Lib                  0.4.24

* vmdpy                   0.2

* xgboost                 1.6.1

* yfinance                0.1.72

* EMD-signal              1.2.3
