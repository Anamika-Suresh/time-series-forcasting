# Retail Sales Time Series Forecasting

## Project Overview

This project focuses on building an end-to-end Retail Sales Forecasting System using Time Series Analysis and Forecasting techniques. The objective is to predict future daily sales for a retail business to support:

- Inventory Planning
- Demand Forecasting
- Promotion Planning

The project compares two forecasting models:

- ARIMA
- Facebook Prophet

---

# Business Problem

Retail businesses often face:

- Overstocking
- Stockouts
- Revenue loss
- Poor demand estimation

This project aims to solve these issues by accurately forecasting future sales trends using historical retail sales data.

---

# Dataset Features

The dataset includes:

- Store ID
- Date
- Sales
- Promotion 
- Holiday
- Store Type / Region

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Arima
- Facebook Prophet
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

## 1. Business Understanding
- Defined forecasting objectives
- Identified business impact and stakeholders

## 2. Data Preprocessing
- Converted date columns to datetime format
- Handled missing values
- Aggregated daily sales data
- Created time-based features

## 3. Exploratory Data Analysis (EDA)
- Trend analysis
- Weekly and yearly seasonality analysis
- Promotion and holiday impact analysis
- Rolling mean visualization

## 4. Stationarity Check
- Performed ADF (Augmented Dickey-Fuller) Test
- Applied differencing for non-stationary data

## 5. Forecasting Models

### ARIMA
- Built ARIMA forecasting model
- Tuned (p,d,q) parameters
- Forecasted future sales

### Facebook Prophet
- Modeled trend and seasonality automatically
- Generated future forecasts with confidence intervals
- Visualized weekly and yearly seasonality

## 6. Model Evaluation

Models were evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

---

# Model Comparison

| Model | MAE | RMSE |
|---|---|---|
| ARIMA | 73.65 | 95.54 |
| Prophet | 44.95 | 59.02 |

## Conclusion

Facebook Prophet outperformed ARIMA with lower MAE and RMSE values, making it more effective for retail sales forecasting.

---

# Key Business Insights

- Mid-week days showed the highest sales activity
- Promotions positively increased sales
- Strong seasonal patterns were identified
- Demand spikes occurred during specific periods

---

# Business Recommendations

- Increase inventory before high-demand periods
- Run promotions during low-sales days
- Use forecasting for automated inventory planning
- Integrate forecasting with supply chain systems

---

# Future Improvements

- Store-level forecasting
- Product-category forecasting
- Deep Learning models (LSTM)
- Real-time dashboard deployment
- Automated retraining pipeline

---



# Forecast Visualizations

The project includes:

- Sales Trend Analysis
- Rolling Mean Plots
- Seasonal Decomposition
- ARIMA Forecast
- Prophet Forecast
- 60-Day Sales Prediction
- Weekly & Yearly Seasonality Components

---

# Author

## Anamika Suresh
GitHub: https://github.com/Anamika-Suresh
