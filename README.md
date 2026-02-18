# LSTM-Stock-Price-Prediction
Overview

This project implements a Long Short-Term Memory (LSTM) neural network to predict next-day stock closing prices using historical market data.

The model is trained on past closing prices and learns temporal dependencies to forecast future price movements.

⚠️ This project is for educational purposes only and does not constitute financial advice.

🚀 Features

Historical stock data retrieval using yfinance

Data preprocessing with MinMaxScaler

Sequence window (lookback) generation

LSTM-based deep learning model

Inverse scaling for real price comparison

Actual vs Predicted visualization

Next-day price forecasting

Model performance evaluation

🧠 Model Architecture

Input: Sliding window time-series sequences

LSTM layer(s)

Dense output layer

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

📊 Evaluation Metrics

The following metrics are used to evaluate performance:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

Directional Accuracy

Directional accuracy measures how often the model correctly predicts price movement direction (up or down).

📉 Example Output

Actual vs Predicted price comparison plot

Highlighted next-day forecast

Model performance summary printed in console








