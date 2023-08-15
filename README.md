# Quora-Duplicate-Questions-Detection
This project aims at determining whether two Quora questions are similar in what they are asking or not using various ML and DL models with an extensive feature engineering.  As a result, this task is essentially a binary classification problem, with a 0/1 response dependent on whether or not the questions are comparable. This project is partially a replication of the cited paper (https://arxiv.org/pdf/1907.01041.pdf).

The dataset was accessed from the Kaggle competition which is the same source as the paper (https://www.kaggle.com/competitions/quora-question-pairs/data).

## Data Overview
The dataset that is presently accessible has been found to be substantially unbalanced. 255,027(63.08 %) of the 404,290 question pairings have a negative (0) label, while 149,263(36.92 %) have a positive (1) label. Observing the dataset, the dataset is being splitted into three sections namely train, validation and test with the ratio of 70:10:20.

## Models used for classification

1. Linear models
    - Logistic Regression with unigrams, bigrams, trigrams, trigrams and hyper-paramater tuning
    - Support Vector Machines with unigrams, bigrams, trigrams, trigrams and hyper-paramater tuning

2. Tree-based models (with 7 features engineered)
   - Decision Tree
   - Random Forest
   - Gradient Boosted Tree

3. Neural Networks
   - LSTM (Long short-term memory) model
   - CBOW (Common bag-of-words) model

