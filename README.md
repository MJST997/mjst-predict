# Twitter Engagement Prediction

This repository contains code for predicting Twitter engagement (likes) using a combination of the BERTweet model and the NRCLex sentiment analysis library.

## Introduction

The goal of this project is to create a machine learning model that can accurately predict the number of likes a tweet will receive based on its content and additional features. The model leverages a pre-trained BERTweet model to analyze the tweet text and the NRCLex library to extract sentiment information. Combining these two powerful tools enables us to predict engagement on Twitter more effectively.

## Emotion Prediction with BERTweet and NRCLex

The emotion prediction process in our model consists of two main steps:

1. Using the pre-trained BERTweet model to generate contextualized embeddings for the tweet text.
2. Utilizing the NRCLex library to extract sentiment features from the tweet text.

By combining the results of these two steps, we can generate a more accurate prediction of the tweet's engagement in terms of likes.

## Code for Engagement Prediction

The code for engagement prediction is divided into several parts:

1. Data preprocessing and feature extraction.
2. Defining and training the BERTweet-based regressor model.
3. Evaluating the model's performance using R2 score.

Please refer to the `main.py` file in this repository for the complete implementation of the engagement prediction process.
