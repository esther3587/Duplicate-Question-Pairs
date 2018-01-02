# MLND_Capstone
Capstone project for Machine learning Nanodegree at Udacity

## Introduction

Quora is a popular website where people can ask and answer all kinds of questions. However, a lot of times people as similar or almost identical questions, which make searching for the best answer difficult.
In this project, I have developed a supervised learning algorithm to detect duplicate questions on Quora.

## Required Libary
 - numpy
 - pandas
 - wordcloud
 - sklearn
 - matplotlib
 - os
 - collections
 - xgboost
 - graphviz

 ## Running
 All the run scripts are in capstone.ipynb file.

 ## Data
 Both training data and test data are available at [Kaggle Quora Competition Website](https://www.kaggle.com/c/quora-question-pairs/data). Unfortunately they are too large to be stored in this repository.

 ## Final result
 Using XGboost model with 6 features I am getting logloss ~ 0.39.
