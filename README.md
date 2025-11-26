

# Portfolio Optimization & Investment Analytics System

This project implements a Python-based portfolio optimization system designed to support data-driven investment decisions. It automates financial analytics, computes optimal portfolio weights, evaluates risk–return metrics, and integrates seamlessly with Power BI for interactive visualization.

---

## Overview

The system analyzes historical asset data, performs mean-variance optimization, generates efficient frontier plots, and produces actionable recommendations for portfolio adjustments.
It is built for students, analysts, and anyone exploring quantitative finance.

---

## Key Features

* Portfolio optimization using the Markowitz mean-variance model
* Automated data cleaning and preprocessing
* Calculation of volatility, expected returns, Sharpe ratio
* Efficient frontier visualization
* Exportable results for Power BI dashboards
* Lightweight modular design (loader, optimizer, metrics, visualizer)
* CSV/Excel-based input and output structure

---

## Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* PyPortfolioOpt (optional)
* Power BI

---

## System Workflow

1. Load historical price data from CSV.
2. Clean, preprocess, and calculate daily returns.
3. Generate covariance matrix and expected returns.
4. Optimize portfolio weights under various constraints (max Sharpe, min variance).
5. Plot the efficient frontier and save results.
6. Export metrics and optimized weights for Power BI.
7. Build dashboards for allocation, performance, and risk analysis.

---

## Project Structure

```
project/
│── data/
│   └── portfolio_data.csv
│── notebooks/
│   └── optimization.ipynb
│── src/
│   ├── data_loader.py
│   ├── optimizer.py
│   ├── risk_metrics.py
│   └── visualizer.py
│── powerbi/
│   └── portfolio_dashboard.pbix
│── results/
│   └── optimized_weights.csv
```

