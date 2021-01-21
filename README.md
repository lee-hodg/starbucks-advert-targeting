# Starbucks Advertising

This project was completed as part of the Udacity Datascience nanodegree.

## Setup

Starbucks wishes to send out some advertising to customers offering a promotion. There is a cost of 0.15 dollars per advert. Although, as we will see
blanket sending to all the users does statistically increase the purchase
rate compared to a control group, it does not increase the revenue sufficiently to offset the cost of sending the advert.

We have some features `V1, ..., V7` that characterize each user. We are not provided with information about what each of these features represent. 

We wish to train a model that uses those features to predict which users
are most likely to make a purchase upon receiving a promotion and then we can target the promotion specifically at these users in such a way that (hopefully) we have a net increase in revenue.

## Data exploration

The first part of the notebook will explore the data. Check if we really did see a statistically significant increase in the purchase rate. 

We then investigate the distribution of the features: which features may be categorical, which need to be normalized? Which features show the largest difference between the control and treatment groups?

## Models

We need train Logistic Regression and XGBoost models to make predictions 
about if a user would likely respond to a promotion and we test the IRR and NIRwwhen each model is used to inform our target group.

Next `

