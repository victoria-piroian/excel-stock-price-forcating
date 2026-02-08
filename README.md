# Stock Price Forecasting Using Time-Series and Regression Models

## Overview
This project focuses on forecasting stock prices using time-series methods and regression-based predictive modeling. Historical price data for Exxon Mobil Corp (XOM) was analyzed to identify trends, patterns, and seasonality, followed by the development and comparison of two forecasting approaches. The workflow includes:

- Historical analysis: Trend detection, seasonality testing, and pattern identification using statistical methods.
- Statistical testing: ANOVA for weekly and monthly seasonality and regression significance testing.
- Time-series modeling: Double exponential smoothing (Holt’s Method) for trend-based forecasting.
- Regression modeling: Multi-feature linear regression using financial and external market variables.
- Sensitivity analysis: Parameter tuning and feature selection for model optimization.
- Model evaluation: Performance comparison using mean absolute deviation (MAD).

---

## Key Features

### Historical Data Analysis
- Trend detection using linear regression
- Weekly and monthly seasonality testing using ANOVA
- Pattern identification through time-series visualization
- External event analysis (e.g. geopolitical impacts on energy markets)

### Time-Series Modeling
- Double Exponential Smoothing (Holt’s Method)
- Parameter optimization using sensitivity analysis
- Multi-step ahead forecasting
- Trend-based forecasting without seasonality components
- Error modeling and residual analysis

### Regression Modeling
- Multi-feature linear regression using:
  - Opening price
  - High and low prices
  - Trading volume
  - External market variables
- Feature selection and correlation analysis
- Causal modeling approach
- Sensitivity analysis with external company stock data
- Comparative model evaluation

### Evaluation
- Mean Absolute Deviation (MAD)
- Forecast vs actual price comparison
- Model accuracy benchmarking
- Error magnitude analysis
- Performance ranking across models
- Trend consistency evaluation

---

## Usage
Clone the repository:
```bash
git clone <repo-url>
```

Install dependencies:
```
pip install pandas numpy scikit-learn matplotlib
```

Run notebooks/scripts to:
- Load historical stock price data
- Perform trend and seasonality analysis
- Train Holt’s Method forecasting model
- Train linear regression forecasting models
- Run sensitivity analysis
- Generate forecasts and error metrics
- Compare model performance

View outputs such as:
- Forecast plots
- Error metrics
- Model comparisons
- Trend analysis figures

---

## Goals
- Model real-world financial time-series data
- Compare classical time-series forecasting with regression modeling
- Evaluate causal vs trend-based forecasting approaches
- Demonstrate feature engineering in financial prediction
- Analyze model robustness under external market shocks
- Support data-driven financial forecasting decisions

---

## Author

Victoria Piroian

University of Toronto

Faculty of Applied Science & Engineering, 2023
