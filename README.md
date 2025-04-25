# Time-Series-Forecasting-of-Stock-Prices
This repository contains my completed Time Series Analysis Project focused on forecasting stock prices using statistical modeling techniques. The project demonstrates how to analyze, preprocess, and forecast time series data using Python.
📊 Project Workflow
1. Data Collection & Preprocessing
Imported stock price data in CSV format

Handled missing values, formatted date-time indices

Visualized trends using rolling mean and standard deviation

2. Stationarity Check
Performed Differencing to make the series stationary

Used Augmented Dickey-Fuller (ADF) Test for confirmation

Visualized ACF and PACF plots to identify lag dependencies

3. Model Building
Built an AutoRegressive (AR) model using statsmodels

Trained model on training set and predicted future values

Evaluated model performance on test data

4. Evaluation Metrics
MAE: Mean Absolute Error

MSE: Mean Squared Error

RMSE: Root Mean Squared Error

MAPE: Mean Absolute Percentage Error

AIC / BIC: For model selection and penalty comparison

5. Visualization
Plotted actual vs. predicted stock prices

Visualized residual errors and diagnostic plots

🛠️ Tools & Technologies
Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Statsmodels, Sklearn

