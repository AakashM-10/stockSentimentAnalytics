# Stock Sentiment Analyses Using News Headlines
Applied Bag of Words Model and predicted sentiments of Stock by Random Forest technique and multinomial Naive Bayes classification models.

# About :
Bag of Words (BOW) is a method to extract features from text documents. These features can be used for training machine learning algorithms. It creates a vocabulary of all the unique words occurring in all the documents in the training set.

In simple terms, it’s a collection of words to represent a sentence with word count and mostly disregarding the order in which they appear.

A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. 

The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts. However, in practice, fractional counts such as tf-idf may also work

# Dataset Description :
The dataset consists of  features include Date from 2000 to 2016, Label either 1 for positive sentiment or 0 for negative sentiment and Top 25 news Headings from which we predict sentiments of stock.

# Understanding files and folders in project :
code.py - Contains the code for the project

StockData.csv - Dataset

# Setting up the project :
The following libraries needs to be installed for the program to run.

Numpy

Pandas

Sklearn

Matplotlib

# Running the program :
Run the program using Google Collaboratory by using the link in code.py or in any Python Interpreter by typing py code.py (tested on Windows 10)
