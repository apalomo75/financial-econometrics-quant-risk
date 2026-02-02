# Financial Econometrics & Quantitative Risk Modeling

This repository contains an end-to-end **quantitative econometrics and risk modeling pipeline** for financial markets.  
The project is designed as an academic–professional portfolio showcasing practical skills in econometrics, time series analysis, volatility modeling, risk measurement, and quantitative portfolio analysis using Python.

The focus is not on isolated models, but on building a **coherent, reproducible workflow** that mirrors how quantitative research, risk, and analytics teams operate in real-world settings.

## Project Scope

The project covers the full quantitative modeling stack applied to financial markets:

- Linear factor models (CAPM, Fama–French) and econometric diagnostics  
- Time series foundations: stationarity, unit roots, cointegration, VAR/VECM  
- Conditional volatility modeling: ARCH, GARCH, GJR-GARCH, EGARCH  
- Tail-risk measurement: Value at Risk (VaR) and Expected Shortfall (ES)  
- Option pricing and Monte Carlo simulation  
- Portfolio construction and optimization  
- Quantitative strategies and systematic backtesting  

All analyses are implemented in Python using Jupyter notebooks, with a strong emphasis on statistical validity, model diagnostics, and interpretability.

## Repository Structure

**notebooks/**
- N01 — Data Engineering & Returns Construction  
- N02 — Linear Models, Factor Models & Diagnostics  
- N03 — Unit Roots, Cointegration & VAR/VECM Dynamics  
- N04 — Conditional Volatility Modeling (ARCH / GARCH / EGARCH)  
- N05 — Tail Risk Modeling (VaR & Expected Shortfall)  
- N06 — Option Pricing & Monte Carlo Methods  
- N07 — Static Portfolio Optimization  
- N08 — Quantitative Strategies & Backtesting  

**data/**
- processed/ — Cleaned and aligned datasets  
- powerbi/ — Export-ready tables for dashboards  

**figures/**
- Model outputs and visual diagnostics  

**tables/**
- Regression and estimation results  

**utils/**
- Helper functions and shared utilities  

Each notebook builds on the previous one, forming a **logically ordered pipeline** rather than a collection of standalone experiments.

## Methodological Approach

- Econometric assumptions are explicitly tested (heteroscedasticity, autocorrelation, normality).
- Models are selected based on statistical diagnostics, not convenience.
- Robust inference techniques are used where classical assumptions fail (e.g. HAC / Newey–West errors).
- Financial stylized facts such as volatility clustering, fat tails, and leverage effects are explicitly modeled.
- Outputs are structured for downstream use in risk management, forecasting, and visualization tools.

## Tools & Technologies

- Python (NumPy, pandas, statsmodels, arch, matplotlib)
- Jupyter Notebooks
- Econometric and time-series modeling frameworks
- Power BI–ready data exports for visualization

## Status

This repository represents a completed and continuously refined quantitative modeling pipeline.  
Future extensions may include additional forecasting models and machine-learning-based risk components.
