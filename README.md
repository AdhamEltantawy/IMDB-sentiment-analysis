# Sentiment Analysis with IMDB Dataset

Sentiment analysis is one of the famous topics in NLP (natural language processing).
The main purpose is to determine (predict) the input review is negative or positive.

This model can be applied in almost any given business to better process their customers feedbacks in more effiencent way.


# Model

Several models were tested and I got the following accuracies:

First Model --> unigram, stemming, remove stop-words, cleaning without removing numbers, Count Vectorizer and Logistic Regression  :  0.85712

Second Model --> unigram, stemming, remove stop-words, cleaning with removing numbers, Count Vectorizer and Logistic Regression  :  0.85424

Third Model --> bigram, stemming, remove stop-words, cleaning with removing numbers, Count Vectorizer and Logistic Regression  :  0.84548

Forth Model --> bigram, stemming, cleaning with removing numbers, Count Vectorizer and Logistic Regression  :  0.87428

Fifth Model --> bigram, lemma, cleaning with removing numbers, Count Vectorizer and Logistic Regression  :  0.87952


# Dataset

The IMDB dataset contains highly polar movie reviews 50k reviews (25k positve and 25k negative). 

The dataset can be downloaded here : IMDB Dataset


# Requirements:

1- Python

2- Pandas

3- Numpy

4- SkLearn

Further requirements can be found in requirements.txt
