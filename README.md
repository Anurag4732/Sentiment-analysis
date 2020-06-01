This repository contains all the relevant information and code for predicting the sentiment for a given set of statements.

The training and data is taken from the website taken from https://datahack.analyticsvidhya.com/contest/linguipedia-codefest-natural-language-processing-1/#About

Approach Taken:
1. Data visualization and Preprocessing. 

2. Feature engineering Like:- Made new feature based on tweet size, Levenshtein distance, lexicon model based.

3. Word embedding by Tf-Idf with max_df = 0.99 and min_df = 5.

4. Use Logistic Regression, RandomForest, GrBoosting, Multinaive Bayees and for parameter tuning RandomSearchCV is used.

5. Evaulation matrix = F1-Score

6. RandomForest at training data = 0.81 and at testing data = 0.78

Working On Deep learning Model:-
ANN and LSTM which is giving 0.81 f1 score ....But i am working on it's hyper parameter.
