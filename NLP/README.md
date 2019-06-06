### Project Overview

 Given references to news pages collected from an web aggregator in the period from 10-March-2014 to 10-August-2014. The resources are grouped into categories that represent pages discussing the same story. News categories included in this dataset include business(b); science and technology(t); entertainment(e); and health(h).

The goal is to predict which class a particular resource belongs to given the title of the resource.


### Learnings from the project

 Tokenization,stopword removal,Vectorization of data(Bag of words and TFIDF),Multiclass Text Classification using Logistic Regression and Multinomial Naive Bayes


### Approach taken to solve the problem

 Preprocess text data with tokenization, stopword removal and splitting data in train and test
Vectorize data using Bag-of-words(Count vactorizer) and TF-IDF approaches
Apply classifiers (Logistic and Multinomial Naive Bayes) to perform multi-class classification


### Challenges faced

 Imbalance classes



