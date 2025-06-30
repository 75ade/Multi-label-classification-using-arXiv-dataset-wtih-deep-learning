# Multi-label classification using the BERT model

## About
This project will be using the BERT model, from Hugging Face, to predict the categories of each research paper in the arXiv dataset, you can find the raw dataset at this link: https://www.kaggle.com/datasets/Cornell-University/arxiv

## Usage
With this project, in case you do not have a strong GPU or enough RAM, it is best for you to run it on platforms which support GPU usage like Google Colab or Kaggle

## Details
In this project we will implement steps as below:
  - Preprocess the data:
    - Extract neccesary columns
    - Preprocess the label data
    - Remove duplicated rows
    - Sampling the data
    - Combine the feature columns
    - Split the data to training, validation and test data

  - Train and evalute the BERT model with the training data (Please note that while training and evaluating we will be using one single threshold for all categories)
  - Finding the optimal thresholds for each category by using 2 methods:
    - ROC
    - PRC

  - Test the model with 3 types of thresholds:
    - Single threhold
    - ROC
    - PRC
