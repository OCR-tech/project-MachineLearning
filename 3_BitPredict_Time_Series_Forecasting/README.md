# Project 3: BitPredict: Time-Series Forecasting with TensorFlow

## Objectives:

- To predict the price of Bitcoin based on historical data with time series forecasting
- To build an ensemble model from several trained time series forecasting models
- To evaluate the model with mean absolute error (MAE) performance metric

## Steps:

1. Data pre-processing
   - Get the series data
   - Format and visualize datasets
2. Model 0: Naive forecast (baseline)
3. Model 1: Dense model (window=7, horizon=1)
4. Model 2: Dense model (window=30, horizon=1)
5. Model 3: Dense model (window=30, horizon=7)
6. Model 4: Conv1D
7. Model 5: RNN (LSTM)
8. Model 6: Dense (multivariate time series)
9. Model 7: N-BEATS algorithm
10. Model 8: Ensemble model
11. Model 9: Dense on full data
12. Compare models

## Usages:

- Open [notebook](https://colab.research.google.com/github/OCR-tech/project-MachineLearning/blob/main/3_BitPredict_Time_Series_Forecasting/notebook.ipynb) in Colab and run the code cells
- Use the trained model to predict the Bitcoin price on test dataset

## Data:

- The dataset is downloaded from [file](BTC_USD_2013-10-01_2021-05-18-CoinDesk.csv), and contains information about the historical price of Bitcoin, including features such as date, open, high, low, close, volume, and market cap.
- Please refer to [Coindesk](https://www.coindesk.com/price/bitcoin) for more details.

## Outcomes:

- A trained model capable of predicting the price of Bitcoin based on historical data
- High accuracy in predicting the price of Bitcoin, with a focus on MAE
  <br><br>

<p align="center"><b>Future price prediction of Bitcoin for next 14 days</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ml3a.png"/>
</div>
<br>
