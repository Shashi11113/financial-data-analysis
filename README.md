# Multi-Company Financial Data Analysis (Python)

## Overview
This project performs an end-to-end financial data analysis on multiple publicly traded companies using Python.  
It combines **historical stock price behavior** with **company fundamentals** to build a multi-factor ranking model.

The notebook is designed to demonstrate real-world data analysis skills commonly used in finance, analytics, and investment research.

---

## Notebook Contents
The analysis is contained in a single Jupyter Notebook (`project.ipynb`) and includes:

- Data ingestion from a live financial API
- Data inspection and validation
- Feature engineering on financial time series
- Risk and return analysis
- Correlation and diversification analysis
- Fundamental analysis
- Cross-sectional merging of price metrics and fundamentals
- Metric scaling and normalization
- Composite scoring and ranking
- Visual interpretation of results

All code, outputs, tables, and charts are rendered directly in the notebook.

---

## Data Sources
- **Market data**: Historical daily stock prices retrieved using `yfinance`
- **Fundamental data**: Company financial metrics retrieved using `yfinance`

Companies analyzed:
- AAPL
- MSFT
- AMZN
- GOOGL
- TSLA

---

## Analysis Workflow

### 1. Price-Based Analysis
- Extracted adjusted closing prices
- Calculated daily, monthly, and yearly returns
- Analyzed rolling volatility and moving averages
- Evaluated correlations between stocks
- Computed cumulative performance
- Derived annualized return, volatility, and Sharpe-like metrics

### 2. Fundamental Analysis
- Retrieved valuation, profitability, leverage, and risk metrics
- Cleaned and standardized financial data
- Handled missing values using domain-appropriate logic

### 3. Feature Engineering & Modeling
- Merged price metrics with company fundamentals
- Applied z-score standardization
- Adjusted metric directionality (lower-is-better vs higher-is-better)
- Built an equal-weight composite scoring model
- Ranked companies based on combined fundamentals and performance

---

## Key Outcome
The final output is a **ranked list of companies** based on a systematic, data-driven multi-factor model that incorporates:

- Market performance
- Risk
- Valuation
- Profitability

This approach mirrors real-world equity screening and factor-based investment analysis.

---

## Project Structure


---

## How to View the Results
1. Open `project.ipynb`
2. Scroll through the notebook
3. All outputs, tables, and visualizations are already rendered

No additional setup is required to view the analysis on GitHub.

---

## Author
Sadam Hashi
