# Data Science and Analytics Internship, DevelopersHub Corporation
# Task 3: Energy Consumption Time Series Forecasting
## Objective
Forecast short-term household energy usage using historical time-based patterns.

## Approach
- Parse and resample time series data
- Engineer time-based features (hour, weekday/weekend, etc.)
- Compare ARIMA, Prophet, and XGBoost models
- Evaluate with MAE and RMSE
- Visualize actual vs forecasted values

# Household Energy Consumption Forecasting
## About the Project
This project forecasts short-term household energy usage using historical power consumption data. Three models, ARIMA, Prophet, and XGBoost, are built and compared to find the best forecasting approach.

## What Was Done
The data was preprocessed from minute-level to hourly/daily, missing values were handled, and time-based features like hour, weekday, and lag values were engineered. Each model was trained on historical data and evaluated on the last 30 days using MAE and RMSE metrics.

## Results & Conclusion
XGBoost performed best due to its ability to leverage engineered lag and temporal features. ARIMA and Prophet captured seasonal trends but were less precise at the hourly level. The project demonstrates that machine learning models can outperform classical statistical methods for granular energy forecasting.


## Skills Gained
-> **Time Series Forecasting**: Implemented ARIMA, Prophet, and XGBoost models

-> **Feature Engineering**: Created temporal features (hour, day, weekend flags) and cyclical encodings

-> **Model Comparison**: Evaluated models using MAE and RMSE metric

-> **Temporal Data Visualization**: Created comprehensive plots for actual vs forecasted values

-> **Residual Analysis**: Analyzed prediction errors and model performance patterns
