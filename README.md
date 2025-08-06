# 📊 Time Series Forecasting – Individual & Team Work

## 📖 Overview

This project focuses on analyzing and forecasting financial time series from the Vietnamese stock market, particularly stock prices and company revenues. It is divided into two parts:

### 1. 🔍 Individual Analysis

Each team member selected a company to analyze. The analysis included:

- Forecasting quarterly revenue and short-term stock prices.
- Testing stationarity using ADF.
- Applying ARIMA models and comparing alternatives.
- Estimating volatility using GARCH models.

### 2. 👥 Group Analysis

Individual results were combined to construct and evaluate an investment portfolio. Key components:

- Portfolio construction using:
  - Minimum variance strategy
  - Maximum expected return strategy
- Forecasting portfolio returns via:
  - Original return series
  - Aggregated forecasts from individual analyses
- Inter-series relationship modeling using:
  - Cointegration tests
  - VAR (Vector Autoregression) models

---

## 🙋‍♂️ My Contributions

This repository includes the parts I personally developed:

### 📌 Individual Report – PVC

- Analyzed PVC (PetroVietnam Chemical and Services Corporation)
- Forecasted:
  - Quarterly revenue for 2025 using the multiplicative trend and seasonal model
  - Stock prices for the first 10 trading days of 2025 using ARIMA
  - Volatility using GARCH

### 📌 Group Report – VAR Modeling

- Implemented the entire VAR analysis section:
  - Selected optimal lag length
  - Estimated the VAR(1) model
  - Performed residual diagnostics
  - Produced forecasts
  - Conducted impulse response and variance decomposition analysis

---

## 📁 Files Included

| File                        | Description                                      |
|-----------------------------|--------------------------------------------------|
| `ts_personal_project.Rmd`   | R code for individual analysis (PVC)            |
| `ts_personal_project.html`  | Rendered HTML report for personal work          |
| `ts_group_contribution.html`| Rendered HTML for VAR section in group report   |
| `PVC_data.csv`              | Dataset used in individual analysis             |
| `G05_print.pdf`             | Full group project report (Vietnamese, PDF)     |

> 🔹 *Note: Only the data for the PVC analysis is included. Group datasets are not available.*

---

## 🛠 Tools & Methods

- **Language**: R  
- **Libraries**: `forecast`, `rugarch`, `vars`, `tseries`, `urca`, `tidyverse`, `ggplot2`  
- **Models**: ARIMA, GARCH, VAR

