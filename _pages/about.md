---
permalink: /
title: "wellcome to Parsa Farinneya's page"
excerpt: "Abdfghjout me" 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I’m an amirkabir university of technology graduate, and I'm fascinated with deep learning, especially interested in Natural Language Process and its use in social networks, rumour detection, data mining, active learning and time series forecasting. I have done several research projects in these areas.


**Rumour detection and verification in social media platforms**
My bachelor thesis is on Rumour detection and verification in social media platforms. I have been working on this project under supervision of [Dr. Hamidian](http://scholar.google.com/citations?user=TuPmndQAAAAJ&hl=en). In this project I used different word embedding from BERT to ROBERTA to represent context of tweet and with the use of source tweet-replies structures and meta data provided by (twitter/ reddit)  to classify if a thread is rumour or not. Alongside rumour detection I had to train a model that determines the stance of the replies to source tweets, which could be helpful on verifying or denying the source rumour. You can find more about this project on [it’s github code] (https://github.com/parsafarinnia/rumoureval2019) and its [blog]().


**Transformer based oil price prediction**

I have also worked on energy price (Brent oil) prediction under supervision of [Dr. Hajizadeh](http://scholar.google.com/citations?user=F82IGnUAAAAJ&hl=en). In this project we experimented with using Transformer attention-based models for time series prediction (in this case Brent oil). Our model outperformed conventional models such as LSTM , MLP , SVR, Gaussian process. Later in this project to improve the performance of the model I used a hybrid model with all the mentioned models, which as we expected improved the accuracy of the prediction. The results of the project were turned into a paper and currently it’s under the review of Elsevier journal for Energy. You can find more about this project on [it’s github code] (https://github.com/parsafarinnia/rumoureval2019) and its [abstract](https://drive.google.com/file/d/12B0rfTif9IESRqrLxWwH7JE3PBgB_Dhp/view?usp=sharing).

**Stock movement with social media information**

Combining what I learned from my previous researches , NLP for social networks and time series forecasting, under supervision of [Dr. nickabadi](http://scholar.google.com/citations?user=pSMNSZwAAAAJ&hl=en) we started to implement a prediction model for stock movement that takes social media information as an input alongside historical price data. We experimented with different methods of using social media info (tweets about certain stocks crawled for top 30 s&p 500 stocks), from varios aggrigations to scoring users based on prediction power and social media status(followers , likes etc). The code for this project is available upon request.

**Active Transfer Learning on text classification**

Currently I'm researching on developing an Active Transfer learning method for text classification. My motivation for this project is to train models that aren’t data hungry to train but can produce high accuracy results. In this research I experiment with finding the write combination of :
- text representation ( Bag of Word, tf_idf, Glove, Bert, Tweet Bert, …)
- model ( MLP with different architectures, SVM, Random forest, ada boost, …)
- active learning query strategy ( Least certainty, Core set, Margin based, ...)
The goal is to train model that needs the least labeled data to hit a certain accuracy.. This project is ongoing and you can read more about this project on [it’s github code] (https://github.com/parsafarinnia/sentiment_new_approach) and its [blog]().

**EMNLP WNUT 2020 shared task2**

In this shared task the goal was to develop a system that can determine if a tweet is informative and provides information on COVID. In this project we had to crawl tweets to get meta data and try different models to get the highest f1. Our system was accepted to workshop and our team (IntelligentCyborgs) are on the [leaderboard](https://arxiv.org/pdf/2010.08232.pdf). You can read more about this project on [it’s github code](https://github.com/parsafarinnia/WNUT2020_task2) and its [page](http://noisy-text.github.io/2020/).



