## Project Title
AAPL Project by RNN in AI 

## Overview
This project focuses on predicting Apple (AAPL) stock prices using deep learning techniques, specifically Recurrent Neural Networks (RNN). The model learns patterns from historical stock data and predicts future price trends.

Dataset is sourced from Kaggle and contains historical stock market data including Open, Close, High, Low, and Volume.

## Objective
To build a time-series forecasting model that can predict future stock prices based on historical market data.

## Dataset
* Source: Kaggle
* Data: AAPL historical stock prices
* Features:
    * Open price
    * Close price
    * High price
    * Low price
    * Volume
     
## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

## Model Used
* Recurrent Neural Network (RNN)
* LSTM (Long Short-Term Memory) (recommended if used)

## Workflow
* Data collection from Kaggle
* Data cleaning & preprocessing
* Feature scaling (Normalization)
* Train-test split (time series split)
* Model building (RNN/LSTM)
* Training on historical data
* Prediction of future prices

## Evaluation
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Visualization of actual vs predicted prices

## Results
* Model captures stock trend patterns
* Good performance on short-term prediction
* Shows ability of RNN in sequential data learning

## Future Improvements
* Use LSTM/GRU for better accuracy
* Add multi-stock prediction system
* Deploy using Streamlit dashboard
* Integrate live stock API for real-time prediction
