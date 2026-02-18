# 📈 LSTM Stock Price Prediction

## Overview

This project uses a Long Short-Term Memory (LSTM) neural network to predict next-day stock closing prices based on historical market data.

The model learns temporal dependencies in time-series data and generates forecasts using a sliding window (lookback) approach.

> This project is for educational purposes only and does not constitute financial or investment advice.

---

## 🚀 Features

- Historical stock data retrieval using `yfinance`
- Data preprocessing with `MinMaxScaler`
- Sliding window sequence generation
- LSTM-based deep learning model
- Inverse scaling for real price comparison
- Actual vs Predicted visualization
- Next-day price forecasting
- Performance evaluation metrics (RMSE, MAE, Directional Accuracy)

---

## 🧠 Model Architecture

- Input: Time-series sequences (lookback window)
- LSTM Layer(s)
- Dense output layer
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam

---

## 📊 Model Evaluation

The model performance is evaluated using:

- **RMSE (Root Mean Squared Error)**  
  Measures overall prediction error magnitude.

- **MAE (Mean Absolute Error)**  
  Measures average absolute difference between actual and predicted values.

- **Directional Accuracy**  
  Measures how often the model correctly predicts price movement direction (up or down).

---

## 📉 Output

The notebook provides:

- Actual vs Predicted price comparison plot
- Highlighted next-day forecast
- Performance summary printed in console
- Optional prediction table with error values

---










