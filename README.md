# Fake-News-Classifier
A data science projects to classify news with Fake News or Real News using different machine learning models like bag of words, LSTM etc.
This is Natural Language Processing Problem.


# Problem Statement

This is a problem to identify wheather a given news is fake or real. The Indepedent variables or factors used here can be title of news or news lines themselves. In the above four notebooks we have tried four different ways to solve this problem.
These four ways are Bag of Words Model, Bag of Words model with TFIDF, RNN LSTM model, Bidirectional RNN LSTM model

# Dataset

The dataset for news is taken from Kaggle https://www.kaggle.com/c/fake-news/. The dataset is quite huge containing thousands of rows, we expect our model to be highly accurate.
Being dataset so huge we cannt upload it on Github because of 25 MB limit. You can refer to the link given for dataset.

# Accuracies of Different model

* Bag of Words CountVectorizer  - 0.9212469237079574
* Bag of Words TFIDF            - 0.9207000273448182
* RNN LSTM                      - 0.92
* RNN Bidirectional LSTM        - 0.9289

# Conclusion

We can see that Deep Learning model RNN Bidirectional LSTM gave a greater accuracy then normal Bag of Words Models and normal LSTM model, thus this should be preferred over Bag of Words models in most NLP related problems incuding this one.
