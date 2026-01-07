# Market-Volatility-Risk-Modeling
A comparative study of GARCH, ML models, and risk metrics (VaR, CVaR) on financial time series

Classical Econometric Models vs Machine Learning Approaches

## Overview
Financial markets exhibit volatility clustering, heavy tails, and regime changes, making risk estimation a non-trivial problem.
This project builds an end-to-end volatility and risk modeling pipeline, comparing classical econometric models (GARCH-family) with machine learning approaches, and evaluates them using industry-standard risk metrics.

## Objectives
- Model and forecast market volatility using GARCH and EGARCH
- Compare classical models with machine learning-based volatility predictors
- Estimate and backtest Value at Risk (VaR) and Conditional VaR (CVaR)
- Evaluate model performance across different market regimes
- Emphasize interpretability, robustness, and validation
  
## Data
Daily price data for selected financial instruments (Nikkei 225)
Data source: public financial market data (Yahoo Finance / CSV)

### Preprocessing
- Log-return computation
- Stationarity testing (ADF test)
- Rolling volatility estimation
- Feature engineering for ML models

## Methodology
### Exploratory Data Analysis
- Return distribution analysis
- Volatility clustering visualization
- Stationarity and autocorrelation checks

### Classical Volatility Models
- GARCH(1,1)
- EGARCH
- Volatility forecasting and comparison with realized volatility

### Machine Learning Models
Feature set:
- Lagged returns
- Rolling volatility
- Moving averages

Models:
- Random Forest Regressor
- Gradient Boosting / XGBoost 
Performance comparison against econometric models

### Risk Estimation
- Parametric VaR (95%, 99%)
- Historical VaR
- Conditional VaR (Expected Shortfall)

### Backtesting & Validation
- VaR breach analysis
- Coverage testing
- Stability across time windows

### Evaluation Metrics

- Forecast error (MSE / MAE)
- VaR violation rate
- Interpretability vs accuracy trade-offs
- Sensitivity to regime changes

## Tech Stack

- Python
- pandas, numpy
- statsmodels, arch
- scikit-learn
- matplotlib / seaborn

## Author

Shachipriya Pattanayak
Computer Science Undergraduate
Interests: Financial Risk, Machine Learning, Quantitative AnalyticsTech Stack

