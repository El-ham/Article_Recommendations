# Article Recommenders

## Introduction
This repository contains code for making recommendations using various techniques on real data from the IBM Watson Studio platform.

## Table of Contents
1. [Exploratory Data Analysis](#exploratory-data-analysis)
2. [Rank-Based Recommendations](#rank-based-recommendations)
3. [User-User Based Collaborative Filtering](#user-user-based-collaborative-filtering)
4. [Content Based Recommendations](#content-based-recommendations)
5. [Matrix Factorization](#matrix-factorization)

## Exploratory Data Analysis <a name="exploratory-data-analysis"></a>
- Descriptive statistics on user-article interactions.
- Exploration and removal of duplicate articles.

## Rank-Based Recommendations <a name="rank-based-recommendations"></a>
- Function to return top n articles based on the number of interactions.

## User-User Based Collaborative Filtering <a name="user-user-based-collaborative-filtering"></a>
- Reformatting data to be shaped with users as rows and articles as columns.
- Function to provide an ordered list of the most similar users to a given user.
- Function to recommend articles to each user based on similar users.

## Content Based Recommendations<a name="content-based-recommendations"></a>
- Implementation of a content-based recommender system.
- Summary of how the content-based recommender works and possible improvements.

## Matrix Factorization <a name="matrix-factorization"></a>
- Setup of user-item matrix for matrix factorization.
- Determination of the number of latent features.
- Exploration of SVD performance on test data and discussion on recommendations.

## Conclusion
Various recommendation techniques have been explored in this repository, providing insights into how to make effective recommendations to users. Further improvements and experimentation can be conducted to enhance recommendation accuracy and user experience.
