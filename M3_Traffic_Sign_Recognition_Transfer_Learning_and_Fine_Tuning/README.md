# Module 3: Traffic Sign Recognition: Transfer Learning and Fine Tuning

## Objectives:
- To classify traffic sign images using fine-tuning pre-trained VGG-16 architecture model in TensorFlow and Keras

## Steps:
1. Data pre-processing
    - Download and extract dataset
    - Create train and validation datasets
    - Create and pre-process test dataset
2. Model inference using VGG-16 for Fine-Tuning
    - Load VGG-16 convolutional base and and instantiate the weights
    - Freeze the initial layers in convolutional base
    - Add classifier to complete the model
    - Compile and train the model
3. Model evaluation
    - Make predictions on validation dataset
4. Deployment
    - Make predictions on test dataset
    - Display the results

## Outcomes:
- The model can be used to classify traffic sign images
- A confusion matrix to visualize the model's performance
<br><br>

<p align="center"><b>Prediction the traffic signs on test dataset</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/module_ml3a.png"/>
</div>
<!-- ![Alt text](https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/module_ml3a.png) -->
<br>

