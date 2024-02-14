# Email Classification using NLP

This project focuses on classifying emails into spam and non-spam categories using Natural Language Processing (NLP) techniques. We'll preprocess the text data, visualize the label distribution, perform feature engineering, and train machine learning models for classification.

## Dataset

The dataset used for this project can be found on Kaggle: [Email Classification - NLP](https://www.kaggle.com/datasets/datatattle/email-classification-nlp)

### Columns

1. **Message Body**: Contains the email content.
2. **Label**: Indicates whether the email is spam or non-spam.

## Tasks

### Task 1: Text Cleaning and Preprocessing

- Load the training and testing datasets.
- Check for missing values and remove them if any.
- Convert all text to lowercase.
- Remove stop words.
- Remove punctuation.
- Perform stemming or lemmatization.

### Task 2: Data Visualization

- Visualize the distribution of the labels in the training dataset using a histogram, bar chart, or pie chart.

### Task 3: Feature Engineering

- Apply text representation techniques:
  - Bag of words
  - TF-IDF

### Task 4: Model Training

- Train SVM model after applying Bag of Words.
- Train SVM model after applying TF-IDF.
- Train Random Forest model after applying Bag of Words.
- Train Random Forest model after applying TF-IDF.

## Evaluation Metrics

Evaluate the performance of the trained models on the testing dataset using the following metrics:
- Accuracy
- Precision
- Recall

## Repository Structure

