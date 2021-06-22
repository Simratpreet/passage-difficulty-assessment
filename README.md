# Problem Statement
We have a dataset from Kaggle where we have texts from different passages and a target column indicating the reading ease of the passage.
This is a regression usecase requiring some NLP skills as well. We need to minimize the rmse metric for the evaluation

## Approaches Followed
I have tried two different kinds of models to predict the reading ease (y) variable -
1. Google Word2Vec with Tree Based Classifiers
2. Google Word2Vec with LSTMs

## Results
Google Word2Vec with Tree Based Classifiers gave lesser rmse of 0.67 compared to LSTM implementation giving 0.73
