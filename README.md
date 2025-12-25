# Multi-Company Financial Data Analysis (Python)

## Overview
This project performs an end-to-end financial data analysis on multiple publicly traded companies using Python.  
It combines **price-based market analysis** with **company fundamentals** to create a multi-factor ranking model.

The goal is to demonstrate real-world data analysis skills used in finance, analytics, and investment research.

---

## Technologies Used
- Python
- pandas
- numpy
- yfinance
- matplotlib
- seaborn
- Jupyter Notebook

---

## Dataset
- **Market data**: Daily adjusted stock prices retrieved via Yahoo Finance (yfinance)
- **Fundamental data**: Company-level financial metrics (valuation, profitability, leverage, risk)

Tickers analyzed:
- AAPL
- MSFT
- AMZN
- GOOGL
- TSLA

---

## Analysis Workflow

### 1. Data Ingestion
- Downloaded 5 years of daily price data
- Extracted adjusted closing prices
- Retrieved company fundamentals via API

### 2. Data Inspection & Cleaning
- Verified data completeness
- Handled missing fundamental values (e.g., dividend yield)
- Ensured consistent ticker alignment

### 3. Price-Based Analysis
- Daily, monthly, and yearly returns
- Rolling volatility and moving averages
- Correlation analysis
- Risk-adjusted performance (Sharpe-like metric)

### 4. Fundamental Analysis
- Valuation metrics (P/E, P/B)
- Profitability (profit margins, ROE)
- Risk and leverage (beta, total debt)
- Sector and industry classification

### 5. Feature Engineering
- Annualized return and volatility
- Risk-adjusted return metrics
- Cross-sectional dataset combining price metrics and fundamentals

### 6. Scaling & Normalization
- Z-score standardization of metrics
- Directional correction (lower-is-better metrics inverted)
- Ensured comparability across different units

### 7. Composite Scoring & Ranking
- Equal-weight multi-factor scoring model
- Ranked companies based on combined fundamentals and performance

### 8. Visualization
- Return distributions
- Correlation heatmaps
- Composite score bar chart
- Valuation vs risk-adjusted performance scatter plots

---

## Key Outcome
The final output is a **ranked list of companies** based on a systematic, data-driven multi-factor model combining:
- Market performance
- Risk
- Valuation
- Profitability

This approach mirrors real-world equity screening and factor-based analysis used in finance.

---

## Project Structure
