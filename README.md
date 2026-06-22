# Financial-Time-Series-Forecasting-System-using-LSTM-Networks

## Overview

This project implements a deep learning-based stock price forecasting system using Long Short-Term Memory (LSTM) networks. The model learns historical stock price patterns and predicts future closing prices by leveraging time-series analysis techniques and sequential deep learning architectures.

The project demonstrates the complete machine learning pipeline, including data collection, preprocessing, feature engineering, model training, evaluation, and visualization.

## Features
Historical stock data collection using Yahoo Finance
Data preprocessing and normalization using MinMaxScaler
Time-series sequence generation using a 100-day sliding window
Stacked LSTM architecture with Dropout regularization
Stock price prediction and trend forecasting
Performance evaluation using RMSE and MAE
Visualization of actual vs. predicted stock prices

## Technologies Used
Python
Pandas
NumPy
Matplotlib
yFinance
Scikit-learn
TensorFlow / Keras (LSTM, Dense, Dropout)
Jupyter Notebook


## Project Workflow

### Data Collection
Retrieved historical stock market data using Yahoo Finance.

 ### Data Preprocessing
Selected closing prices.
Applied MinMax normalization.
Split data into training and testing sets.

###Feature Engineering
Created 100-day sequential windows for model training.
Analyzed trends using Moving Averages (MA) and Exponential Moving Averages (EMA).

### Model Development
Built a stacked LSTM neural network with Dropout layers.
Trained the model using the Adam optimizer and Mean Squared Error loss.

### Evaluation
Generated predictions on unseen test data.
Evaluated performance using RMSE and MAE.


## Results
Evaluation Metrics
RMSE: 22.71
MAE: 18.70

## Key Observations
Successfully captured long-term and short-term stock market trends.
Generated smooth and realistic forecasts without significant noise.
Predictions closely followed actual market movements, especially during strong trend periods.
Demonstrated the effectiveness of LSTM networks for financial time-series forecasting.

##Future Improvements
Incorporate technical indicators such as RSI, MACD, and Bollinger Bands.
Experiment with GRU and Transformer-based architectures.
Perform hyperparameter optimization.
Develop a real-time stock forecasting dashboard.
