# Sentiment Analysis

## Overview

This project performs sentiment analysis on airline tweets to classify them into **negative**, **neutral**, or **positive** sentiments. It leverages various machine learning models, including Logistic Regression, Support Vector Machine (SVM), Random Forest, and an Ensemble model using Voting Classifier. The project includes data preprocessing, feature extraction using TF-IDF, hyperparameter tuning, and comprehensive model evaluation.

## Features

- **Data Retrieval:** Loads and preprocesses tweet data from a CSV file.
- **Text Preprocessing:** Cleans text data by tokenization, removing stopwords, and filtering non-alphabetic tokens.
- **Feature Extraction:** Utilizes TF-IDF Vectorizer to convert text data into numerical features.
- **Model Training:** Implements Logistic Regression, SVM, and Random Forest classifiers with hyperparameter tuning using Grid Search.
- **Ensemble Learning:** Combines individual models using Voting Classifier for improved performance.
- **Evaluation:** Assesses model performance using metrics such as Accuracy, Precision, Recall, F1 Score, and detailed classification reports.

## Installation

### Prerequisites

- Python 3.7 or higher
- pip
