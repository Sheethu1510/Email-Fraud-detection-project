# Email-Fraud-detection-project using Machine Learning
# Overview

This project aims to detect fraudulent emails using machine learning techniques. It classifies emails as either spam (fraudulent) or ham (legitimate) using Natural Language Processing (NLP) and a Naïve Bayes classifier.

# Dataset

The dataset used in this project consists of labeled email messages:

ham: Legitimate emails

spam: Fraudulent emails (phishing, scams, etc.)

# Features & Preprocessing

Text Cleaning: Removed punctuation, numbers, and converted text to lowercase.

Vectorization: Used TF-IDF (Term Frequency - Inverse Document Frequency) to convert text into numerical format.

Label Encoding: Converted spam to 1 and ham to 0.

# Model Used

Multinomial Naïve Bayes: A probabilistic model commonly used for text classification.

# Visualizations

Class Distribution: A bar plot showing the number of spam vs. ham messages.

Word Clouds: Visualization of common words in spam and ham emails.

Confusion Matrix: Shows model performance by comparing actual vs. predicted classifications.

# Results

The model achieves a good accuracy in distinguishing fraudulent emails from legitimate ones.
