# Time series Analysis and Forecasting for Stock market

This project involves analyzing and forecasting **Tata Consultancy Services (TCS)** stock prices using classical time series models and deep learning.

The notebook includes:
- Data collection from Yahoo Finance
- Data preprocessing and visualization
- Model building with ARIMA, SARIMA, Prophet, and LSTM
- Final comparison of all models with performance metrics

---

## Tools & Libraries Used

- **Python** (Jupyter Notebook)
- **Pandas, NumPy, Matplotlib, Seaborn, Plotly** – Data handling & visualization
- **Statsmodels** – ARIMA & SARIMA models
- **Prophet (by Facebook)** – Trend and seasonality forecasting
- **TensorFlow/Keras** – Deep learning (LSTM)
- **Scikit-learn** – Metrics and data scaling

---

## Dataset

- **Source**: Yahoo Finance (TCS.NS)
- **Duration**: Jan 2019 – Dec 2024  
- **Features**: Date, Open, High, Low, Close, Volume

---

## Models Used

| Model    | Description                         |
|----------|-------------------------------------|
| **ARIMA**   | Classical model for stationary time series |
| **SARIMA**  | Seasonal ARIMA for time series with cycles |
| **Prophet** | Forecasting with trend + seasonality (Meta) |
| **LSTM**    | Deep learning for sequential data |

---

## Final Model Comparison

| Metric | ARIMA | SARIMA | Prophet | LSTM |
|--------|-------|--------|---------|------|
| RMSE   | 178.84 | 157.2 | 370.78 | 195.44 |
| MAE    | 147.07 | 132.29 | 349.14 | 163.86 |
| MAPE   | 3.41 | 3.08 | 8.33 | 3.82 |

---
## Key Highlights

- End-to-end pipeline: From raw data to model comparison  
- Clean visualizations: Trends, ACF/PACF, seasonality  
- Deep Learning (LSTM) with 3D input and normalization  
- Clear evaluation with RMSE, MAE, MAPE  
- **portfolio project**

---

Project Done by :
 **Maguvarshini M**
---

  Run the Jupyter notebook to see everything: data, models, plots, forecasts, and comparison.

---

## Feedback

If you liked this project or have suggestions, feel free to ⭐ the repo !

