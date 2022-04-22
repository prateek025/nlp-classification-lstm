# Natural Language Processing using Neural Networks

## I. Repository Overview
- This repository contains tutorials that cover different NLP applications leveraging Neural Network models. Currently 1 tutorial notebook is available in this repository:
  1. `nlp_classfication_lstm.ipynb`

## II. Tutorial notebooks details
1. **`nlp_classfication_lstm.ipynb`**
    - This notebook covers how to classify text data using an `LSTM` model build in `Tensorflow` framework.
    - Dataset used for analysis is the [Clickbait Dataset](https://www.kaggle.com/datasets/amananandrai/clickbait-dataset) taken from Kaggle website.
    - Two different binary classification LSTM models are built on this dataset to identify if a given news headline text a clickbait headline or not.
      - Model 1 calculates new embeddings during model developement.
      - Model 2 uses [Stanford's pre-trained glove embeddings](http://nlp.stanford.edu/data/glove.6B.zip)
    - This notebook covers the usual data cleaning steps for processing text data, and other functionalites in `tensorflow.keras.preprocessing.text` and `tensorflow.keras.preprocessing.sequence` to transform and prepare text data so that it can used in an LSTM model.
