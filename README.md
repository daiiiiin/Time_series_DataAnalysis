# Time_series_DataAnalysis
study  

## 1. Overview
This project is about working with time series data. This project was done after reading a paper (https://dl.acm.org/doi/abs/10.14778/3476311.3476341) about analyzing time series data. The dataset used in this project is from Cagle. It is time series data, and the goal is to make predictions using some of the tools used in time series analysis.  

## 2. Study
- To analyze time series data, we need to preprocess it.  
  - Process timestamps at appropriate time intervals  
- I set a baseline and if it was worse than that model's performance, I didn't consider it.  
- stationary test : The ‘Stationarity Test’ test if the time series has a stationarity property, i.e., the statistical properties like error means, variances and moments, do not change with time. Stationarity helps define the characteristics of time series data in a certain way and is an important assumption when applying many statistical estimation and testing techniques.  
- Partial AutoCorrelation Plot : Shows the pure correlation between two time series data with different time differences. The correlation between the original time series data (y_k) and the time-lagged k time series data (y_t-k), removing the influence of any time series data contained between the two points in time.  
- ARIMA, SARIMA  
- prophet : This is a time series forecasting library released by Facebook. It automatically performs forecasts based on time-series data without statistical knowledge, and is said to be relatively robust to outliers and missing data. It has the advantages of high accuracy, fast speed, and easy model modification with intuitive parameters.  
- Finding optimal parameters with Auto ARIMA

## 3. Conclusion
Through this assignment, I was able to learn what to consider when preprocessing time series data and learn about different time series analysis techniques.  
***
Utilize the following data sets "KAG_energydata_complete.csv" in zip file. This code was created with Colab.

If you have any questions, you can email here.  
dsekdls725@seoultech.ac.kr  
