# Project 2: SkimLit: Natural Language Processing

## Objectives:

- To classify medical abstract sentences into different sentence classes using NLP models
- To build and train a model with 200,000+ labelled randomized abstracts of PubMed 200k RCT dataset
- To evaluate the model with prediction probabilities

## Steps:

1. Data pre-processing
   - Download and visualize text dataset
   - Get lists of sentences
   - Make numeric labels
2. Model 0: baseline model
   - Building a model
   - Model evaluation
3. Model 1: Conv1D with token embeddings
   - Convert text into numbers using text vectorization
   - Creating custom text embedding
   - Creating datasets
   - Building a model
   - Model evaluation
4. Model 2: Feature extraction with pretrained token embeddings
   - Building a model
   - Model evaluation
5. Model 3: Conv1D with character embeddings
   - Creating character-level token vectorizer instance
   - Creating character-level embedding
   - Building a model
   - Model evaluation
6. Model 4: hybrid embeddings (token embeddings + character embeddings)
   - Building a model
   - Combining token and character data into dataset
   - Model evaluation
7. Model 5: Transfer learning (pretrained token + character + positional embeddings)
   - Create positional embeddings
   - Building a model
   - Create tribid embedding dataset
   - Model evaluation
8. Comparision performance
   - Make preditions and evaluation
   - Evaluate model on test dataset
   - Find most wrong
9. Make example prediction

## Usages:

- Open [notebook](https://colab.research.google.com/github/OCR-tech/project-MachineLearning/blob/main/2_SkimLit_Natural_Language_Processing/notebook.ipynb) in Colab and run the code cells
- Use the trained model to classify medical abstract sentences into their respective classes

## Data:

- The dataset is downloaded from [PubMed 200k RCT dataset](https://github.com/Franck-Dernoncourt/pubmed-rct), and contains information about medical abstracts, including features such as class labels and text data.

## Outcomes:

- A trained model capable of classifying medical abstract sentences into their respective classes
- High accuracy in classifying medical abstract sentences, with precision, recall, and f1 scores
- A confusion matrix to visualize the model's performance
  <br><br>

<p align="center"><b>Prediction the medical abstract with labels</b></p>
<div align="center">
  <img src="https://github.com/OCR-tech/OCR-tech/blob/main/docs/img/project_ml2a.png"/>
</div>
<br>
