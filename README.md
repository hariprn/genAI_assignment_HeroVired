# Stock Market Prediction Using Economic Indicators

## Overview

This project performs a comprehensive financial data analysis and predictive modeling study using multiple stock market datasets and macroeconomic indicators. The objective is to understand how technical indicators, interest rates, commodities, global indices, futures contracts, and currency movements influence stock prices, and to build predictive models for market forecasting.

The project focuses primarily on the Dow Jones Industrial Average (DJI) while incorporating additional datasets from NASDAQ, NYSE, Russell, and S&P 500 indices.

---

## Problem Statement

Financial markets are influenced by numerous interacting variables including macroeconomic conditions, global market behavior, commodity prices, and currency exchange rates. Traditional price-only prediction models often ignore these external dependencies.

The goal of this project is to:

* Clean and preprocess multi-source financial datasets
* Analyze relationships between stock prices and economic indicators
* Study time-series trends and volatility patterns
* Evaluate sector and global index contributions
* Measure macroeconomic and currency impacts on stock movements
* Build machine learning and deep learning models for stock price prediction

---

## Datasets Used

The analysis includes processed datasets for:

* Dow Jones Industrial Average (DJI)
* NASDAQ Composite
* New York Stock Exchange (NYSE)
* Russell Index
* S&P 500 Index

Each dataset contains:

* Historical stock prices
* Technical indicators (EMA, RSI, Momentum, ROC)
* Interest rates and treasury yields
* Commodity prices (Oil, Gold, Brent)
* Global market indices
* Futures market data
* Currency exchange rates

---

## Project Workflow

### 1. Data Cleaning and Preprocessing

* Missing value detection and forward filling for time-series consistency
* Outlier detection using statistical techniques
* Return calculation and feature engineering

### 2. Correlation and Feature Analysis

* Correlation heatmaps for technical and macroeconomic variables
* Identification of strongest predictors of stock price movement

### 3. Time Series Trend Analysis

* Seasonal decomposition of stock prices
* Study of long-term trend, seasonal patterns, and irregular shocks
* Comparison with interest rates and commodity price movements

### 4. Volatility Analysis

* Rolling standard deviation calculation
* Bollinger Band visualization
* Detection of crisis-level volatility periods

### 5. Sector and Stock Contribution Analysis

* Grouping of major stocks into technology, finance, and energy sectors
* Comparative performance analysis

### 6. Global Market Comparison

* Correlation study between DJI and international indices
* Identification of strongest global market dependencies

### 7. Macroeconomic Impact Modeling

* Regression analysis using interest rates, commodity prices, and bond yields
* Interpretation of economic influence on stock movements

### 8. Futures Market Analysis

* Study of relationships between stock prices and futures contracts
* Identification of leading indicators

### 9. Currency Impact Study

* Analysis of exchange rates and dollar strength on equity performance

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## Repository Structure

```
data/              → Stock datasets
notebooks/         → Analysis notebooks
report/            → Final project report
README.md          → Project documentation
requirements.txt   → Python dependencies
```

---

## Key Insights

* Rising interest rates generally suppress stock market performance.
* Technical indicators are strong short-term predictors.
* Gold behaves as a safe-haven asset during crises.
* Futures markets often provide early signals of price movement.
* Technology sector performance strongly influences modern stock indices.
* LSTM models outperform traditional regression methods for sequential forecasting.

---

## Future Improvements

* Add financial news sentiment analysis
* Implement transformer-based forecasting models
* Deploy real-time prediction dashboard
* Integrate portfolio optimization techniques

---

## Author

Project developed as part of a financial data analysis on stock market prediction using economic indicators.

