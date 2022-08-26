# starbucks-rewards
Predicting Starbucks offer conversions - Data Scientist nanodegree capstone project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Libraries used: numpy, pandas, matplotlib, seaborn, sklearn, catboost, lightgbm, xgboost. Python version: 3.7.12

## Project Motivation<a name="motivation"></a>

Once every few days, Starbucks sends out an offer to users of the Starbucks rewards mobile app. These offers could be informational (advertisement), discount or Buy One Get One Free (BOGO) offer. Giving each customer an offer that they would most likely respond to would increase offer conversion rates and sales, user engagement on the app as well as overall customer satisfaction. 

In this project, I combine simulated transaction, demographic and offer data and build machine learning models to predict whether a customer will respond to an offer. 

## File Descriptions <a name="files"></a>

+ capstone-starbucks-rewards-v2.ipynb : notebook with end-to-end code
+ data/portfolio.json: portfolio dataset with information about each offer (duration, type, difficulty, reward and channels)
+ data/profile.json: profile dataset with demographic data for each customer (age, gender and income)
+ data/transcript.json: transcript dataset with records for transactions, offers received, offers viewed and offers completed and the time of those records

## Results<a name="results"></a>

The main findings of the code can be found in this [Medium post](https://medium.com/@yen_290/predicting-starbucks-offer-conversions-with-xgboost-179ce3b3f22c).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
The dataset and project design were sourced from Udacity and Starbucks. Some of the functions used in the code were taken from exercises as part of the Udacity Data Scientist nanodegree 2022. I would also like to thank my family, friends and colleagues for their continuous support that helped me through this nanodegree. :)
