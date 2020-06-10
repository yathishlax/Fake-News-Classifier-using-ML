Fake-News-Classifier
Goal:
This project is basically focused on identifying the fake news using NLP and machine learning.
It is applied in following two vectorizing methods.
1.Bag of words model.
2. TF-IDF model

Source:
The source of this dataset is from Kaggle.com
https://www.kaggle.com/c/fake-news/data#

About the dataset:
Dataset contains articles containing the fake news and so machine learning algorithms are used to classify them.
It is split into train and test data for building the model.

Features:
id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable

Libraries Used:
pandas- it offers data structures and operations for manipulating numerical tables and time series.
Numpy – for numerical operations.
Stopwords – It is used to remove stop words from the sentences.
PorterStemmer – used for stemming, identifying the base stem word.
CountVectorizer – it is used to convert a collection of text documents to a matrix of token counts in Bag of words model.
TFIDFVectorizer – it is used to convert a collection of raw documents to a matrix of TF-IDF features. Where TF- IDF imputes weights to words based on TF*IDF.
Sklearn - For Machine Learning operations.
train_test_split – for splitting data into training and testing purpose.
matplotlib.pyplot – for visualizing the observations
metrics – to measure accuracy related factors such as confusion matrix, accuracy score etc.
MultinomialNB – Navyes bayes classifier for predicting text data.
PassiveAggressiveClassifier – Linear model classifier for predicting text data


Approach

•	Text Cleaning
•	Vectorizing using CountVectorizer/TF-IDF
•	Train test split
•	Apply Models
•	Hyperparameter tuning on best model
•	Calculating accuracy of both CountVectorizer/TF-IDF
