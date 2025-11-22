# Energy Demand & Solar Generation Forecasting using ARIMA

## Problem Statement
Predicting energy demand and solar generation is crucial for efficient energy planning. We analyzed **load and solar generation data for 2016** to detect patterns and forecast future values using **time series modeling**.

## Methodology
1. **Data Exploration:** Visualized load and solar generation to understand daily and seasonal patterns.  
2. **Stationarity Check:** Used **Augmented Dickey-Fuller test** to ensure the time series were stationary.  
3. **ARIMA Modeling:** Built **ARIMA models** (p=2, d=0, q=2) for load and solar series, using **80% of data for training** and 20% for testing.  
4. **Model Evaluation:** Calculated **RMSE** and plotted **actual vs predicted values** to assess performance.

## Results
- Load Model RMSE: **~7715**  
- Solar Generation Model RMSE: **~2486**  
- Forecasts captured the **general patterns and daily/seasonal fluctuations** in both series.

## Conclusion
The ARIMA models successfully predicted future energy demand and solar generation, demonstrating **time series analysis, statistical modeling, and forecasting skills**. These insights can help in **energy planning and management**.
