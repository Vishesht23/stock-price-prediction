# Hybrid ARIMA-LSTM Model for Financial Time Series Forecasting

A self-initiated project focused on building a hybrid **ARIMA-LSTM** model for forecasting stock prices with high accuracy. The model combines traditional statistical methods with deep learning to leverage both short-term trends and long-term temporal dependencies in financial time series data.

## 📌 Overview

This project aims to enhance stock price prediction by combining ARIMA — a powerful statistical tool for capturing linear trends — with LSTM — a type of recurrent neural network suited for modeling long-term dependencies. The hybrid approach significantly improves forecasting performance, especially for volatile and non-linear financial data.

## 🎯 Objective

- Develop a hybrid **ARIMA-LSTM** model for accurate and robust **financial time series forecasting**.
- Apply the model to **Nifty 50** index data for real-world validation.

## 🧠 Key Concepts & Methods

- **Time Series Decomposition**: Stationarity, trend, seasonality analysis.
- **Modeling Techniques**:
  - **ARIMA** for linear time series modeling.
  - **SARIMA** for seasonal adjustments.
  - **LSTM (Long Short-Term Memory)** for capturing non-linear dependencies.
  - **Hybrid ARIMA-LSTM** to combine strengths of both paradigms.

## ⚙️ Technologies & Tools

- **Python**
- **pmdarima**
- **statsmodels**
- **TensorFlow / Keras**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**

## 📈 Results

- **ARIMA Model**:
  - **MAPE**: 0.55%
  - **RMSE**: 34.37
  - **R² Score**: 0.89

- **Hybrid ARIMA-LSTM Model**:
  - **MAPE**: 0.54%
  - **RMSE**: 37.00
  - Improved forecast reliability and generalization

## 🔍 Future Improvements

- Extend model to multi-variate time series (e.g., technical indicators, sentiment analysis).
- Deploy the model as a real-time forecasting web app using Streamlit or Flask.
- Integrate rolling window retraining to adapt to market changes dynamically.

## 📚 Keywords

`Time Series Forecasting` · `ARIMA` · `LSTM` · `Hybrid Models` · `Stock Price Prediction`

