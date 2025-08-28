# Stock-Market-Price-Prediction-with-ML

Stock Price Prediction (AAPL)

This project focuses on predicting the closing price of Apple Inc. (AAPL) stock using historical data and machine learning techniques. Financial markets are inherently noisy and complex, but predictive models can still capture meaningful patterns. The project applies both traditional machine learning models and deep learning methods to compare their performance on stock price forecasting.

The dataset is collected from Yahoo Finance using the yfinance library. After preprocessing and cleaning the data, the models are trained and evaluated to understand their strengths and limitations in a real-world stock prediction task.

Features

Automated data collection using yfinance

Data preprocessing, cleaning, and visualization

Implementation of multiple models:

Linear Regression (as a baseline)

Random Forest Regressor (non-linear machine learning approach)

LSTM (Long Short-Term Memory neural network for time-series forecasting)

Model evaluation and comparison using error metrics (MSE, RMSE)

Visualization of actual vs. predicted stock prices to assess model performance

Main libraries used:

yfinance

pandas

numpy

matplotlib

seaborn

scikit-learn

tensorflow / keras

# Results

Linear Regression: provides a simple baseline for comparison

Random Forest: captures non-linear relationships and improves accuracy

LSTM: outperforms other models by leveraging time-series patterns in stock data

Visualization of predicted vs. actual stock prices demonstrates the effectiveness of the models, with LSTM showing the best alignment.

Future Work

Experiment with advanced deep learning models (GRU, Transformer-based models)

Perform hyperparameter optimization for better accuracy

Extend the framework to handle multiple stocks simultaneously

Deploy as an interactive web application using Streamlit or Flask
