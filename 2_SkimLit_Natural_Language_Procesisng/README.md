# Project 2: SkimLit: Natural Language Processing

## Objectives:
- To classify medical abstract sentences into different sentence classes using NLP models
- To build and train a model with 200,000+ labelled randomized abstracts of PubMed 200k RCT dataset
- To evaluate the model with prediction probabilities

## Steps:
1. Data pre-processing
    - Download and visualize text dataset
    - Create helper functions
    - Convert text into numbers using text vectorization
    - Turn tokenized text into character and positional embeddings
2. Building a model
    - Build several deep learning text models
    Create an ensemble model from the pretrained models
3. Training a model
   - Train a model using trained dataset
4. Model Evaluation
   - Make predictions on validation data
5. Deployment
   - Make predictions on custom medical abstracts

## Usages:
- Open [notebook](https://colab.research.google.com/github/OCR-tech/project-DataScience/blob/main/2_SkimLit_Natural_Language_Processing/notebook.ipynb) in Colab and run the code cells
- Use the trained model to classify medical abstract sentences into their respective classes

## Data:
- The dataset is downloaded from [PubMed 200k RCT dataset](https://github.com/Franck-Dernoncourt/pubmed-rct), and contains information about medical abstracts, including features such as class labels and text data.

## Outcomes:
- A trained model capable of classifying medical abstract sentences into their respective classes
- High accuracy in classifying medical abstract sentences, with precision, recall, and f1 scores
- A confusion matrix to visualize the model's performance
<br><br>

<p align="center"><b>Prediction the medical abstract with labels</b></p>

![Alt text](https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ml2a.png)
<br>