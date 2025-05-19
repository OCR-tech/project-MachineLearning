# Project 3: BitPredict: Time-Series Forecasting with TensorFlow

## Objectives:
- To predict the price of Bitcoin based on historical data with time series forecasting
- To build an ensemble model from several trained time series forecasting models
- To evaluate the model with performance metric of MAE

## Steps:
1. Data pre-processing
    - Get the series data
    - Format and visualize datasets
    - Turn data into windowing dataset
    - Prepare data for univariate and multivariate time series
2. Building a model
   - Build a serie of time series forecasting models
   - create an ensemble model form the pretrained models
3. Training a model
   - Train the model using trained dataset
4. Model Evaluation
   - Make predictions on validation data using a trained model
5. Deployment
   - Make predictions for the Bitcoin price on test dataset

## Usages:
- Open in Colab and run the [code](https://colab.research.google.com/github/OCR-tech/project-MachineLearning/blob/main/3_BitPredict_Time_Series_Forecasting/notebook.ipynb)
- Use the trained model to predict the Bitcoin price on test dataset

## Data:
- The dataset is downloaded from [Food-101](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101) and [TensorFlow Datasets (TFDS)](https://www.tensorflow.org/datasets/overview) and contains information about food images, including features such as class labels and image data.

## Outcomes:
- A trained model capable of predicting the price of Bitcoin based on historical data
- High accuracy in predicting the price of Bitcoin, with a focus on mean absolute error (MAE)
- A confusion matrix to visualize the model's performance
<br><br>

<p align="center"><b>Future price prediction of Bitcoin for next 14 days</b></p>

![Alt text](https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ml3a.png)
<br>