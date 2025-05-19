# Project 1: Food Vision: Transfer Learning and Fine Tuning

## Objectives:
- To classify a dish from a given food image across 101 different food classes
- To build a model by applying transfer learning and fine-tuning with TensorFlow
- To train the model with 75000+ images of the Food101 dataset

## Steps:
1. Data pre-processing
    - Import and explore datasets
    - Create preprocessing functions
    - Batch and prepare datasets
    - Create modelling callbacks
    - Setup mixed precision training
2. Building a model
    - Build a feature extraction model using transfer learning
    - Fine-tune the feature extraction model
3. Training a model
    - Train the model using trained dataset
4. Model evaluation
    - Make predictions on food images using validation dataset
    - Evaluate for precision, recall, and f1 scores
    - Create a confusion matrix, and find the most wrong predictions
5. Deployment
   - Make predictions on custom food images with prediction probabilities

## Usages:
- Open [notebook](https://colab.research.google.com/github/OCR-tech/project-DataScience/blob/main/1_FoodVision_using_Transfer_Learning_and_Fine_Tuning/notebook.ipynb) in Colab and run the code cells
- Use the trained model to classify food images into their respective categories
<!-- - Save the trained model for future use -->

## Data:
- The dataset is downloaded from [Food-101](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101) and [TensorFlow Datasets (TFDS)](https://www.tensorflow.org/datasets/overview), and contains information about food images, including features such as class labels and image data.

## Outcomes:
- A trained model capable of classifying food images into 101 different classes
- High accuracy in classifying food images, with a focus on precision, recall, and f1 scores
- A confusion matrix to visualize the model's performance
<br><br>

<p align="center"><b>Prediction the Food with prediction probabilities</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ml1a.png"/>
</div>
<!-- ![Alt text](https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ml1a.png) -->
<br>