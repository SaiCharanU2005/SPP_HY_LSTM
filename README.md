# SPP_HY_LSTM
Stock Price Prediction using Hybrid LSTM + GCN
By:
Sai Charan U (VU22CSEN0300283)




1. Project Overview

This project implements a Hybrid Deep Learning Model combining LSTM (Long Short-Term Memory) and Graph Convolutional Network (GCN) for stock price prediction.

LSTM captures temporal dependencies

GCN captures structural relationships

Applied on Apple (AAPL) stock data




2. Model Architecture

LSTM Layer → Extracts time-series patterns

GCN Layer (Linear approximation) → Enhances feature representation

Fully Connected Layer → Final prediction




3. Dataset

Source: Yahoo Finance (via yfinance)

Stock: AAPL

Time Range: 2020 – 2023




4. Technologies Used

Python

PyTorch

NumPy

Scikit-learn

Matplotlib

yfinance




5. Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score




6. Results

The model demonstrates the ability to learn stock price trends and produce reasonable predictions with low error.


7. Future Improvements

Replace Linear GCN with real Graph Convolution (PyTorch Geometric)

Multi-stock correlation graph

Attention mechanisms

Hyperparameter tuning
