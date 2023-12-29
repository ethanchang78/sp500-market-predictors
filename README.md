# S&P 500 Market Predictions
## Overview
This project focuses on predicting the log returns of the S&P 500 stock market index using machine learning and deep learning models. The models implemented include Random Forest, LSTM (Long Short-Term Memory), and GRU (Gated Recurrent Unit) networks. The project leverages historical stock market data and technical indicators to forecast future market movements.

## Installation
### Prerequisites
- Python 3.x
- pip package manager

## Data
The data for this project is fetched using the yfinance library, focusing on the S&P 500 index (symbol: ^GSPC). The data spans from January 1, 2011, to December 31, 2023.

## Features
The following technical indicators are used as features:
- Log Returns
- Simple Moving Average (SMA)
- Exponential Moving Average (EMA)
- Relative Strength Index (RSI)
- Moving Average Convergence Divergence (MACD)
- Volume
  
## Models
### Random Forest
The Random Forest model is built using sklearn.ensemble.RandomForestRegressor. Hyperparameter tuning is performed using GridSearchCV.

### LSTM Model
The LSTM model is constructed using the tensorflow.keras library. It uses a sequential model with LSTM and dense layers.

### GRU Model
Similar to the LSTM, the GRU model is built using tensorflow.keras and includes GRU and dense layers.

## Results
The models are evaluated based on Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). The performance is visualized using matplotlib plots comparing actual and predicted log returns.

## Usage
To run the Random Forest model:
- Set up the data and features as described in the Data and Features sections.
- Train the model using the Random Forest section of the notebook.
  
To use LSTM and GRU models:
- Prepare the dataset suitable for LSTM/GRU.
- Train the models as per the instructions in their respective sections.
