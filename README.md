# Recommendation_engine_IBM

## Introduction
This project is part of Udacity Data Science Nano degree. The object of this project is to make recommendations to the users about new articles they may like based on the database from IBM Watson Studio platform, with the interactions between users and existing articles recorded.

## IBM Watson Studio Platform
IMB Watson website :
https://dataplatform.cloud.ibm.com/home?context=wdp

## Contents
This main jupyter notebook to complete this goal is Recommendations_with_IBM.ipynb, where you can find the following major contents:
- I.   Exploratory Data Analysis

In the first step, we need to understand the basic statistics of the database, clean and sort the data.

- II.  Rank Based Recommendations

In the second step, we need to rank the article based on its interaction frequency with the users as ratings are unavailable.

- III. User-User Based Collaborative Filtering

In the third step, we reframe the data structure for user-user based collaborative filtering, providing recommandations from similar users.

- IV.  Matrix Factorization

In the last step, we use matrix factorization to make recommendations.

## Description of Files
- I. Recommendation Engine - Contains the Python notebook of the whole project
- II. data - Contains two CSV files:
           - `articles_community.csv` - contains 1056 rows and 5 columns namely doc_body, doc_description, doc_full_name, doc_status, and article_id.
           - `user_item_interactions.csv` - contains 45,993 rows and 3 columns namely article ids, title, and email. Basically, gives info about which user is interacting with                                                 which article

## How to use
Clone the repository, download the data folder, Python notebook named 'Recommendations_with_IBM.ipynb', and simply run it.
