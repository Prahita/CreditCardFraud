# CreditCardFraud

This repository contains the elements of the final project I completed for my Machine Learning Class. I built a Neural network to detect instances of credit fraud.

# Data

The dataset I chose to work with is named “ Credit Card Fraud Detection” on Kaggle. The dataset contains transactions made by European credit cardholders in September 2013. It includes legitimate and fraudulent transactions, with highly imbalanced class distribution, as fraudulent transactions are relatively rare compared to legitimate ones. 
The dataset consists of numerical features obtained from a PCA transformation for privacy reasons, and the actual features are not disclosed. These variables V1 through V28 are labeled as such from the PCA transformation can be interpreted as private information such as bank name, social security, location, store details

You can find the Kaggle dataset file in the repository or linked here: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Model

I chose to utilize a neural network to model this dataset because the advantage this architecture provides is pattern recognition, which is similar to how credit card transactions are marked as fraudulent. More importantly, fraud patterns grow different each year, which makes this choice all the more important. Typically, simple classification models like Logistic Regression, or feature recognition models like Random Forest and Decision Trees are utilized to model credit card fraud in machine learning. Like these model choices, Neural Networks also can identify non-linear relationships and tend to be prone to overfitting. 

