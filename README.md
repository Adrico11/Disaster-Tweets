## Disaster Tweets Classification (Kaggle competition)

### Goal of the project
Build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t
The scores mentioned below are thos obtained on a submission test sample and correspond to the f1-scores of my predictions

Here is the link to the competition : https://www.kaggle.com/c/nlp-getting-started/overview

### Contents of the files in this repo
The three jupyter notebooks in this repo each contain a different approach to solving this problem, with increasing complexity :
- Kaggle ML.ipynb : machine learning models (Logistic regression, Naive Bayes, K-Nearest Neighbours, Random forest, Gradient Boosting...) benchmarked (Best : 0.79313 with a Naive Bayes model) 
- Kaggle DL.ipynb : implementation of deep neural networks for NLP tasks with LSTMs and RNNs (Best : 0.79987 with a Bidirectionnal RNN model)
- Kaggle BERT.ipynb : use of a pre-trained transformer for classification with BERT (Best : 0.83... => **top 10% of submissions !!**)

### Main implementation steps :



