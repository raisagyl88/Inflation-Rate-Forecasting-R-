# Inflation Rate Forecasting Using ARIMA Models

This project applies time series analysis to forecast monthly inflation rates using manually specified ARIMA models in R. The analysis covers data from July 2016 onwards and was developed as part of a university coursework in time series and machine learning.

## 📌 Project Overview

- Visualized the original and differenced inflation rate data.
- Identified stationarity and suitable ARIMA(p, d, q) structure using ACF and PACF.
- Fitted ARIMA models using `Arima()` (manual specification only).
- Compared models based on AIC and diagnostics.
- Forecasted inflation for the next 12 months with 95% confidence intervals.

## 🔍 Key Findings

- Differencing was required to achieve stationarity.
- ARIMA(0,1,1) with drift was selected as the best-fitting model.
- Forecasts suggest a slight upward trend in inflation, but at a reduced rate.

## 📁 Files

- `report.pdf`: Summary of analysis, results, and plots.
- `code.txt`: R code used for the entire modeling process.

## 🛠️ Tools & Libraries

- R with `forecast`, `ggplot2`, `stats`, `Rcpp`
- Manual ARIMA modeling (no `auto.arima()`)

## 📈 Forecast Output

The final model provides a clear 12-month forecast trajectory, aiding potential policy insights based on inflation trends.
