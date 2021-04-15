# ReducingMarketWaste_HackerearthCompetition

## Problem statement :

The company has products which can be used for hiring assessments. The task is to **predict the probability percentage that a client will purchase a product from the features provided in the dataset**.

## Dataset Description : 

The dataset contains the following files :

       1. train.csv : 7007 x 23  
       2. test.csv  : 2093 x 22
       3. sample_submission.csv : 5 x 2

The main challenge in this problem was to clean the dataset. The dataset had multiple **missing values** in various columns. Also. some of the features were **categorical** in nature. So it had to be converted into integral values. Once the dataset was cleaned, training it and making prediction was quite easy.


I have used **XGBoost** algorithm to train the data. It performed excellent with an **accuracy of 95.38027** 

The link for the competition is as follows : https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-reduce-marketing-spend/problems/
