# Email Spam Detector Using NLP

This project is a simple yet effective spam detection system for emails using Natural Language Processing (NLP) techniques and a Support Vector Classifier (SVC). It utilizes a labeled dataset of emails to train a model capable of classifying new emails as either spam or not spam.

---

## Dataset

The dataset used in this project was taken from Kaggle:  (https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset)

---

## Features

- Preprocessing of email text using NLP techniques 
- Vectorization 
- Classification using Support Vector Classifier (SVC)
- Model evaluation 
- An interactive cell at the end for testing custom email texts

---

##  Results

The model achieved the following performance on the test set:



          precision    recall  f1-score   support

       0       0.98      1.00      0.99       856
       1       1.00      0.94      0.97       290

accuracy                           0.98      1146
