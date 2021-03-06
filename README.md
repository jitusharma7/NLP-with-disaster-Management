# NLP-with-disaster-Management

The aim of the project is to build a model that can predict that whether a tweet is related to disaster or not based on tweet content.
## Table of Content
  * [Overview](#Overview)
  * [Problem_Definition](#Problem_Definition)
  * [Dataset_Description](#Dataset_Description)
  * [Exploratory_Data_Analysis](#Exploratory_Data_Analysis)
  * [Text_Preprocessing](#Text_Preprocessing)
  * [Model_Building](#Model_Building)
  * [Result](#Result)
  * [Credit](#Credit)
  
## Overview
Twitter has become an important communication channel in times of emergency.The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. 


 ## Problem_Definition
 In this competition, need to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.
 
 
 ## Dataset_Description
 The dataset consists of the following attributes:

Each sample in the train and test set has the following information:

* The text of a tweet
* A keyword from that tweet (although this may be blank!)
* The location the tweet was sent from (may also be blank)


## Exploratory_Data_Analysis
* Comment length distribution

  <img src="/comment%20length.png" width="300">



## Text_Preprocessing
* Remove white sapce
* Remove stop word
* Tokenize word
* Dropping two features 'Keyword', 'Location'


## Model_Building
* LSTM Deep learning model built
* model compile with binary cross entropy,adam optimizer,accuracy metrics
* Analyzed result with 5 different model, model result is as follows:-

<img src="/NLP_Model.PNG" width="600">


## Result
* Deep learning with Bert , perform better wuth highest accuracy - 84%. 
* Among various machine learning model , SVM classifer with word2vec recall value is highest.
* Recall is one of the main parameters to evaluate model .


  <img src="/accuracy.png" width="300">
  
  
  <img src="/loss.png" width="300">
  

## Credit
[kaggle](https://www.kaggle.com/) - This project has been done on this competitive platform.

