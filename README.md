# retail-sales-time-series-forecasting
Developed a time series forecasting model for U.S. retail sales using Holt-Winters exponential smoothing, capturing trend, seasonality, and economic shocks to improve prediction accuracy.

# Retail Sales Time Series Forecasting

## Overview
This project analyzes U.S. monthly retail sales data and develops a forecasting model using Holt-Winters exponential smoothing. The goal is to capture long-term trends, recurring seasonal patterns, and external shocks such as COVID-19 to generate accurate future sales predictions.

---

## Objective
To build a reliable time series forecasting model capable of predicting retail sales for the next 12 months and evaluating its performance against baseline approaches.

---

## Business Problem
Retail organizations depend on accurate sales forecasts to manage:

- Inventory levels  
- Supply chain operations  
- Staffing and logistics  
- Financial planning  

Inaccurate forecasts can lead to stockouts, overstock, and revenue loss. This project addresses these challenges by applying time series modeling techniques.

---

## Dataset
- U.S. Monthly Retail Sales dataset  
- Time frequency: Monthly  
- Includes historical sales values over multiple years  

---

## Methodology

### Data Preparation
- Cleaned and structured time series data  
- Converted date column into datetime format  
- Set time index for proper time series modeling  

---

### Exploratory Analysis
- Visualized overall trend and seasonality  
- Identified recurring seasonal patterns  
- Observed impact of economic disruptions (e.g., COVID-19)  

---

### Model: Holt-Winters Exponential Smoothing

The model captures:

- **Level** → baseline sales  
- **Trend** → long-term growth or decline  
- **Seasonality** → recurring monthly patterns  

This approach is well-suited for retail data with strong seasonal behavior.

---

### Forecasting
- Generated forecasts for the next 12 months  
- Compared predictions with actual values (where available)  

---

### Model Evaluation
- Metric: Root Mean Squared Error (RMSE)  
- Compared against a seasonal naive baseline  

---

## Results

- Holt-Winters model significantly outperformed the seasonal naive model  
- Successfully captured:
  - Long-term upward trend  
  - Seasonal fluctuations  
  - COVID-related disruption and recovery  

---

## Key Insights

- Retail sales exhibit strong seasonal patterns (monthly cycles)  
- External shocks (e.g., COVID-19) create temporary deviations  
- Holt-Winters effectively adapts to both trend and seasonality  
- Time series models outperform simple baseline methods  

---

## Business Value

- Improves demand forecasting accuracy  
- Supports inventory and supply chain planning  
- Helps anticipate seasonal demand spikes  
- Enables data-driven retail decision-making  

---

## Limitations

- Model assumes consistent seasonal patterns  
- Does not include external variables (e.g., promotions, weather)  
- Performance may degrade under extreme structural changes  

---

## Future Improvements

- Incorporate exogenous variables (economic indicators, promotions)  
- Test advanced models (ARIMA, SARIMA, Prophet)  
- Perform cross-validation for time series  
- Automate retraining pipeline  

---

## Project Structure

- `.ipynb` → analysis and forecasting model  
- `.csv` → forecast outputs  
- `data/` → dataset reference  

---

## Tools Used

- Python  
- pandas  
- statsmodels  
- matplotlib  

---

## Author
Shaghayegh Malekshahi  
Master’s in Data Science  
