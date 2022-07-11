#1
## SmsSpam_Filtering
**An implementation of a Spam Filter in Python that uses the Naive Bayes and KNN Model to classify emails as spam or ham.**
## Classifiers:-
**Naive Bayes:**
- BernoulliNB
- MultinomialNB
- GaussianNB

**KNN:**
- With k=5

**Feature Extraction:**
- CountVectorizer
- TfidfVectorizer


#2

# Stack-Overflow-Tag-Prediction



Stack Overflow is the largest, most trusted online community for developers to learn, share
their programming knowledge, and build their careers. Stack Overflow is something which every
programmer use one way or another. Each month, over 50 million developers come to Stack Over-
flow to learn, share their knowledge, and build their careers. It features questions and answers on
a wide range of topics in computer programming. The website serves as a platform for users to
ask and answer questions, and, through membership and active participation, to vote questions
and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg.
As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000
questions in late August 2015. Based on the type of tags assigned to questions, the top eight most
discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.


This notebook will be divided in 2 parts:

PART 1 : Cleaning data and EDA
PART 2 : Classical classifiers implemented (SGC classifier, MultiNomial Naive Bayes Classifier, Random Forest Classfier.

##Problem Statemtent
Suggest the tags based on the content that was there in the question posted on Stackoverflow.

1.2 Real World / Business Objectives and Constraints
 
 1. Predict as many tags as possible with high precision and recall.

2. Incorrect tags could impact customer experience on StackOverflow.

3. No strict latency constraints.


2. Machine Learning problem

2.1 Data

2.1.1 Data Overview

Refer: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data All of
the data is in 2 files: Train and Test.

The questions are randomized and contains a mix of verbose text sites as well as sites related
to math and programming. The number of questions from each site may vary, and no filtering has
been performed on the questions (such as closed questions).

Data Field Explaination
Dataset contains 6,034,195 rows. The columns in the table are:

2.1.2 Example Data point

3. Exploratory Data Analysis

3.1 Data Loading and Cleaning
