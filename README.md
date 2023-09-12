# IMDb Sentiment Analysis

## Introduction

This project is a sentiment analysis of the IMDb movie review dataset. The dataset contains 50,000 reviews, 25,000 of which are labeled as positive and 25,000 as negative. The goal of this project is to build a model that can accurately classify a review as positive or negative. The dataset can be found [here](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

## Data Preprocessing

The data was preprocessed using the following steps:

1. Remove HTML tags
2. Remove non-alphabetic characters
3. Convert to lowercase
4. Remove stopwords

## Vectorization and Tokenization

Two methods are used: vectorize and tokenize the data:

1. CountVectorizer
2. Tokenizer

## Model

- For CountVectorizer, Machine Learning models were used: Random Forest and logistic Regression.
- For Tokenizer, Deep Learning models used: GRU

## Result

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | 0.85     |
| Logistic Regression | 0.88     |
| GRU                 | 0.88     |
