# retail_demand_forecasting

✅ Retail Demand Forecasting
This project uses historical sales data from a retail store to predict future product demand. Using Python, Pandas, and Statsmodels, we analyzed daily and monthly trends, performed time series decomposition, and implemented a SARIMA model to forecast demand. The model effectively captures seasonality and trends and is evaluated using RMSE, MAE, and MAPE metrics.

📌 Project Aim
Develop a time series forecasting model to predict the demand for products in a retail store using historical sales data

## 📖 Problem Description

Retailers often struggle with inventory optimization due to fluctuating customer demand. This project uses historical **order demand data** to forecast future demand using time series modeling techniques. The goal is to aid better inventory management and reduce stockouts or overstocking.

## 📊 Exploratory Data Analysis (EDA)

- ✅ Converted date columns to datetime format
- ✅ Aggregated order demand daily and monthly
- ✅ Plotted:
  - Daily demand trend
  - Monthly demand trend
  - Distribution of order quantities
  - Correlation heatmap of numerical features

## 📉 Time Series Analysis

- ✅ Performed **seasonal decomposition** to analyze:
  - Trend
  - Seasonality
  - Residuals
- ✅ Applied **SARIMA** (Seasonal ARIMA) for demand forecasting
- ✅ Visualized forecast with confidence intervals

## 📈 Forecasting Model

- Model: `SARIMAX` from `statsmodels`
- Parameters: `order=(1,1,1), seasonal_order=(1,1,1,7)`
- Forecast Horizon: 30 days
- Evaluation Metrics:
  - `RMSE` (Root Mean Square Error)
  - `MAE` (Mean Absolute Error)
  - `MAPE` (Mean Absolute Percentage Error)

## 🔧 Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn**
- **Statsmodels**
- **scikit-learn** (for evaluation metrics)

