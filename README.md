# eCommerce-NLP
Sentiment Analysis and Recommendation Prediction

* Machine Learning Models Application on Womens Clothing ECommerce Reviews 'Predication'
* NLTK Text Processing Application on Womens Clothing ECommerce Reviews
* VADER Application on Womens Clothing ECommerce Reviews 'Sentimental Analysis'

#Introduction

This analysis will focus on using Natural Language techniques to find broad trends in the written thoughts of the customers. The goal is to predict whether customers recommend the product they purchased using the information in their review text.

One of the challenges in this study is to extract useful information from the Review Text variable using text mining techniques. The other challenge is that we need to convert text files into numeric feature vectors to run machine learning algorithms.

# Dataset

The data is a collection of 22641 Rows and 10-column variables. Each row includes a written comment as well as additional customer information. Also, each row corresponds to a customer review, and includes the variables:

* Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
* Age: Positive Integer variable of the reviewer's age.
* Title: String variable for the title of the review.
* Review Text: String variable for the review body.
* Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
* Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
* Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
* Division Name: Categorical name of the product high-level division.
* Department Name: Categorical name of the product department name.
* Class Name: Categorical name of the product class name.

![175719760-b685fe1d-84ce-4451-8aa1-1c8c2c73bcec](https://user-images.githubusercontent.com/108016592/175766953-0ebbdeb2-9044-4bbe-84a1-58fde0c737a4.png)

## Methodology
### General Feature Extraction 'Data Understanging'
* Import the Dataset
* Summary Information
* Summary STAT
* Word counts
* Characters count
* Average characters per word
* Stop words count
* Count punctuations
* Count numeric digits
* URLs
* Emails
* 
### Preprocessing and Cleaning
* Lower case
* Contraction to Expansion
* Emails removal
* URLs removal
* Remove punctuations
* Remove HTML Tags
* Convert Accent Chars
* Remove Stop Words
* Rare words removal
* Remove Extra Spaces
* Stemming NLTK 
* Lemmatizing NLTK

### Word Cloud and EDA
* EDA Target
* EDA IDV
* EDA IDV - DV
* WordCloud
* Tokenizing

### VADER 'Sentimental Analysis'

### Data Splitting & (Voctrization - TFIDF)
* Data Splitting X,y
* Voctrization
* TFIDF

### Machine Learning Models 
- Build the Models 'Train the Models'
-        Random Forest Classifier
-        Gradient Boosting Classifier
-        Histogram-based Gradient Boosting Classification Tree
-        AdaBoost Classifier
-        Extra Trees Classifier
-        K Neighbors Classifier
-        Naive Bayes Classifiers
-        Naive Bayes Classifier for Multivariate Bernoulli
-        Decision Tree Classifier
-        Logistic Regression Classifier
-        Logistic Regression CV Classifier
-        Stochastic Gradient Descent Classifier
-        Linear Perceptron Classifier
-        XGBoost Classifiers
-        Support Vector Machines Classifiers
-        Linear Support Vector Classification
-        Multilayer Perceptron Classifier
- Predication X_test
- Models Evaluation
-       Accuracy Score
-       Classification Report
-       Confusion Matrix

## VADER Result
![175719844-a5f3ebf4-bf03-4a4b-9e1a-70721cac6712](https://user-images.githubusercontent.com/108016592/175767515-5485392b-8f38-4fbc-a634-27e10346416c.png)

## Machine Learning Result 
![175719896-c05b3109-8c7c-48e8-9941-b768831ee17e](https://user-images.githubusercontent.com/108016592/175767542-7d07ae2e-bfca-4b9e-b191-03b453fc810f.png)
