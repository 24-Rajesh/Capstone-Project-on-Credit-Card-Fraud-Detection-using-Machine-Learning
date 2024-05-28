# Capstone-Project-on-Credit-Card-Fraud-Detection-using-Machine-Learning

Credit-Card-Fraud-Detection

# Problem Statement:

A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash. It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. We have to build a classification model to predict whether a transaction is fraudulent or not.

# Context:

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for

These are the steps that will be carried out in this project: Data Sourcing,Data Analysis,Model Building,Model Evaluation

We will also be creating an “evaluate_model” function that will be used to get the metric scores of our models for evaluation. The metrics used are: Accuracy Score: Accuracy is a metric used in classification problems used to tell the percentage of accurate predictions. We calculate it by dividing the number of correct predictions by the total number of predictions.

# These are the steps that will be carried out in this project:

1-Data Sourcing 

2-Data Analysis

3-Model Building

4-Model Evaluation

# Challenges Faced 

The challenge is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.

Main challenges involved in credit card fraud detection are:

-Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.

-imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones

-Data availability as the data is mostly private.

-Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.

-Adaptive techniques used against the model by the scammers.

# How to tackle these challenges?

The model used must be simple and fast enough to detect the anomaly and classify it as a fraudulent transaction as quickly as possible.

-Imbalance can be dealt with by properly using some methods which we will talk about in the next paragraph

-For protecting the privacy of the user the dimensionality of the data can be reduced.

-A more trustworthy source must be taken which double-check the data, at least for training the model.

-We can make the model simple and interpretable so that when the scammer adapts to it with just some tweaks we can have a new model up and running to deploy.

# Model Evaluation and Accuracy

We will also be creating an “evaluate_model” function that will be used to get the metric scores of our models for evaluation. The metrics used are:

Accuracy Score: Accuracy is a metric used in classification problems used to tell the percentage of accurate predictions. We calculate it by dividing the number of correct predictions by the total number of predictions.
