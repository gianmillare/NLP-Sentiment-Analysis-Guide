# NLP Sentiment Analysis Guide

A repository of lessons I learned from a course on [Natural Language Processing by Coursera](https://www.coursera.org/learn/twitter-sentiment-analysis/home/welcome), specifically on sentiment analysis.

This was an introductory machine learning course. I was interested in this because I had never built a model that was centerred around Natural Language Processing. As a new experience, I wanted to know how industry experts would use human languages/words to train a computer to identify things like good and bad reviews.

If you are interested in the lessons taught in this course, you may look below for an overview, or click [here to to view the entire notebook](https://nbviewer.jupyter.org/github/gianmillare/NLP-Sentiment-Analysis-Guide/blob/main/NLP_Sentiment.ipynb). Enjoy!

<hr>

Data Snapshot: A database full of tweets consisting of positive tweets (labeled 0) and a subset of negative tweets (labeled 1).

![](images/data.png)

<hr>

Process 1: I wanted to visualize the words found in good and bad tweets. Below shows the distribution of positive tweets.

![](images/good.png)

<hr>

... And here is a visualization of the distribution of negative tweets.

![](images/bad.png)

<hr>

Data Cleaning: I used string.punctuation to remove punctuations, and nltk.stopwords to remove unnecessary words. Tokenization was used to vectorize the final subset of words.

![](images/tokenization.png)
