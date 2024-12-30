# SPAM-SMS
Overview

This project focuses on developing an AI model to classify SMS messages as either spam or legitimate (non-spam). The dataset consists of SMS messages labeled as "spam" or "ham" (legitimate), which are preprocessed and transformed into numerical features for training and evaluation. The aim is to create a robust model capable of accurately distinguishing spam messages from legitimate ones.

Objectives

Preprocess SMS data to prepare it for machine learning.

Convert text into numerical features using techniques like TF-IDF or word embeddings.

Train and evaluate classifiers such as Naive Bayes, Logistic Regression, and Support Vector Machines.

Achieve high performance using evaluation metrics like accuracy, precision, recall, and F1-score.

Dataset

The dataset contains SMS messages labeled as:

Spam: Messages classified as unsolicited or promotional.

Ham: Messages classified as legitimate.

Project Workflow

1. Data Preprocessing

Text Cleaning:

Removed punctuation, numbers, and special characters.

Lowercased all text for uniformity.

Tokenization: Split text into individual tokens (words).

Stopword Removal: Eliminated commonly used words with little significance (e.g., "is," "and").

Feature Extraction: Transformed the text into numerical representations using:

TF-IDF (Term Frequency-Inverse Document Frequency).

Optional embeddings such as Word2Vec or GloVe.

2. Model Training

Trained and tested multiple classifiers, including:

Naive Bayes: For probabilistic text classification.

Logistic Regression: For binary classification.

Support Vector Machines (SVM): For optimal classification margins.

3. Model Evaluation

Evaluated the models using metrics such as:

Accuracy: Overall correctness of the model.

Precision: Proportion of correctly identified spam messages.

Recall: Proportion of actual spam messages correctly identified.

F1-Score: Harmonic mean of precision and recall.

Results

Developed a high-performing model that accurately classifies SMS messages as spam or ham.

Achieved balanced performance across all evaluation metrics.

