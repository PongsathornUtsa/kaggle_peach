# Disaster Tweet Classification with BERT

## Overview
This repository contains the implementation of a binary classification model to identify whether a given tweet is about a real disaster or not. We utilize the BERT model from the `simpletransformers` library to achieve this classification task.

## Model
The model is based on `bert-base-uncased` provided by Hugging Face's transformers. We fine-tuned this model on a dataset of tweets, where each tweet is labeled as 0 (not about disaster) or 1 (about disaster).

## Performance
The model achieved a score of **0.81765** on the test dataset. This metric reflects the accuracy of the model in classifying tweets accurately as being about real disasters or not.


## Dataset
The dataset used for training is sourced from the [Kaggle NLP Disaster Tweets Competition](https://www.kaggle.com/competitions/nlp-getting-started/leaderboard#). It is divided into training and validation sets. The test results mentioned above were obtained on a separate test set provided as part of the competition.
