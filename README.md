Multivariate VECM and ARIMA Forecasting of Exchange Rate, Interest Rate & CPI

👤 Analyst: Ganesh Wagh
📅 Date: 2025

## 📌 Executive Summary

This project applies econometric methods to forecast key macroeconomic indicators — exchange rates, short-term interest rates, and the Consumer Price Index (CPI). By combining Vector Error Correction Models (VECM) with ARIMA models, the analysis compares multivariate and univariate forecasting approaches to identify which method provides more accurate and reliable forecasts.

Key objectives:

Explore long-run relationships between the variables using cointegration analysis.

Model both short-run dynamics and long-run equilibrium adjustments through VECM.

Benchmark performance against ARIMA-based univariate forecasts.

Evaluate forecast accuracy using statistical metrics and visualization.

📂 Data Overview

Source: Publicly available macroeconomic datasets (e.g., central bank, IMF, FRED).

Variables studied:

Exchange Rate

Short-term Interest Rate

Consumer Price Index (CPI)

Period covered: Multiple years (exact period as per dataset).

Transformations: log transformations, differencing for stationarity, and standardization where needed.

🛠 Methodology

Exploratory Data Analysis (EDA)

Visual inspection of trends, seasonality, and volatility.

Statistical summaries of the three time series.

Stationarity & Cointegration Tests

Augmented Dickey–Fuller (ADF) & KPSS tests for unit roots.

Johansen’s cointegration test to determine number of long-run relationships.

Modeling

VECM: Captures cointegration and long-run equilibrium between variables.

ARIMA: Independent univariate forecasting for each series as a benchmark.

Forecasting & Evaluation

Multi-step ahead forecasts generated for each model.

Accuracy assessed using RMSE, MAE, and MAPE.

Visualization of forecast performance.

📑 Key Findings

Evidence of cointegration between Exchange Rate, Interest Rate, and CPI.

VECM effectively models long-run relationships and provides better forecasts over longer horizons.

ARIMA performs competitively in short-term forecasting but lacks structural insight.

Results highlight the importance of multivariate models in macroeconomic forecasting.

📈 Recommendations

Policymakers and analysts should rely on VECM for medium-to-long-term forecasting where macro linkages matter.

ARIMA can be used as a quick baseline for short-term projections.

Extend the model with exogenous factors (oil prices, GDP growth, trade balances) to improve forecasting accuracy.

Automate rolling forecasts for continuous monitoring
