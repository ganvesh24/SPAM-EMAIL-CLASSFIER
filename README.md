# Spam Email Classifier using Naive Bayes

## Project Overview
A machine learning model that automatically detects whether a given SMS or email 
message is spam or legitimate (ham). Built using Natural Language Processing (NLP) 
techniques and the Naive Bayes algorithm on a real-world dataset of 5,574 messages.

## Problem Statement
Every day, millions of spam messages flood inboxes — promoting fake offers, phishing 
links, and scams. This project builds an intelligent classifier that can automatically 
filter spam messages with high accuracy using machine learning.

## Dataset
- Name: SMS Spam Collection Dataset
- Source: Kaggle / UCI Machine Learning Repository
- Size: 5,574 SMS messages
- Labels: Spam (747 messages) and Ham/Not Spam (4,827 messages)

## Approach
1. Data loading and exploration using pandas
2. Text preprocessing — lowercasing, punctuation removal, stopword removal
3. Feature extraction using TF-IDF Vectorization (3000 features)
4. Model training using Multinomial Naive Bayes
5. Model evaluation using accuracy, precision, recall, and confusion matrix

## Results
- Accuracy: 97.8%
- Precision: 98%
- Recall: 94%
- F1 Score: 96%

## Technologies Used
- Python 3
- pandas, numpy
- scikit-learn
- NLTK
- matplotlib, seaborn
- Google Colab

## How to Run
1. Open spam_classifier.ipynb in Google Colab
2. Run all cells in order
3. Test your own message at the end!
