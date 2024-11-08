# Netflix Movie Recommendation System

## 1. Project Overview

Netflix is all about connecting people to the movies they love. Their recommendation system, **CinematchSM**, predicts whether someone will enjoy a movie based on how much they liked or disliked other movies. The goal of this project is to enhance the existing Cinematch system by experimenting with alternative approaches to improve prediction accuracy.

### Problem Description
Netflix is looking to improve the Cinematch system by implementing alternative recommendation methods to predict whether a user will enjoy a movie. 
The goal is to beat Cinematch by improving the accuracy of predictions. A solution that significantly improves predictions could have a considerable impact on the business by providing better personalized recommendations for customers.

### Problem Statement
Netflix has provided anonymous rating data and challenges us to build a model that outperforms the current Cinematch system by at least **10%** in accuracy, which is measured by how closely the predicted ratings match the actual ratings given by users.

## 2. Data Source

The dataset for this project is provided by Netflix, and it includes a large collection of movie ratings provided by users. You can access the dataset and related rules from the following sources:

- [Netflix Prize Data](https://www.kaggle.com/netflix-inc/netflix-prize-data)
- [Netflix Prize Rules](https://www.netflixprize.com/rules.html)
- [Netflix Tech Blog](https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429)
- [Research Paper](http://courses.ischool.berkeley.edu/i290-dm/s11/SECURE/a1-koren.pdf) on Collaborative Filtering and Matrix Factorization

## 3. Objective

- **Goal**: Predict the rating a user would give to a movie they haven’t rated yet.
- **Performance Metrics**:
  - **RMSE (Root Mean Squared Error)**: Minimize the difference between predicted and actual ratings.
  - **MAPE (Mean Absolute Percentage Error)**: Minimize the percentage error between predicted and actual ratings.
