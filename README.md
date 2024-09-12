Description
A machine learning-based email spam detection system using the Naive Bayes classifier. This project demonstrates how to preprocess text data, train a spam detection model using Scikit-learn, and evaluate its performance using accuracy, confusion matrix, and classification report.
# Email Spam Detection

## Overview
This project implements an email spam detection system using Python and Scikit-learn. The model uses a Naive Bayes classifier to differentiate between spam and ham emails based on text data. It involves text preprocessing, feature extraction using CountVectorizer, and performance evaluation using metrics like accuracy, confusion matrix, and classification report.

## Features
- **Preprocessing of Email Data**: Handles missing data, renames columns, and converts labels to numerical values.
- **Feature Extraction**: Utilizes CountVectorizer for converting text data into numerical features.
- **Naive Bayes Classifier**: A simple yet powerful algorithm for text classification.
- **Performance Metrics**: Evaluates the model with accuracy score, confusion matrix, and detailed classification report.
- **Data Visualization**: Plots data distribution and confusion matrix for better insights.

## Dataset
The dataset used in this project contains labeled email messages with two categories: "ham" (non-spam) and "spam". It was loaded from a CSV file named `spam.csv`.

How It Works
The dataset is preprocessed by dropping unnecessary columns and converting labels to numerical values (0 for ham, 1 for spam).
The email text is vectorized using CountVectorizer, which converts it into a matrix of token counts.
The data is split into training and test sets to evaluate the model's performance.
A Naive Bayes classifier is trained on the training data and tested on the test data.
The script outputs the model's accuracy, confusion matrix, and classification report, which provides detailed metrics on its performance.

Results
The Naive Bayes model achieved an accuracy of approximately 98% on the test set, demonstrating its effectiveness in identifying spam emails.
