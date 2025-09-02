# 📧 Email & SMS Spam Classifier
A Machine Learning project to classify Email and SMS messages as Spam or Ham (Legitimate) using Natural Language Processing (NLP).

🚀 Project Overview

Spam messages are a growing challenge in communication, often used for phishing or scams.
Traditional keyword-based or rule-based filters cannot keep up with evolving spam patterns.

This project develops a robust ML-powered spam detection system with 99% accuracy using Multinomial Naive Bayes, making it scalable for real-world applications.

🛠 Problem Statement

Spam causes loss of productivity and exposes users to security risks.

Rule-based methods fail because spammers constantly change tactics.

Goal: Build a machine learning classifier that automatically identifies spam with high accuracy, precision, and recall.

🔑 Solution Approach

Data Preprocessing

Cleaned and normalized text.

Removed stopwords, tokenized, applied stemming.

Converted text to numerical features with Bag of Words (BoW) and TF-IDF.

Model Training & Evaluation

Trained Logistic Regression, SVM, Random Forest, Multinomial Naive Bayes.

Multinomial Naive Bayes outperformed others.

Evaluation Metrics

Accuracy: 99%

Precision: 0.98 (minimizing false positives)

Recall: 0.99 (catching nearly all spam)

📊 Key Results

Dataset size: ~10,000 labeled messages (spam & ham).

Training Accuracy: 99%

Test Accuracy: 95–97%

Prediction Speed: < 50ms per message → suitable for real-time spam detection.

🧰 Tech Stack

Language: Python

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, nltk

Algorithms: Multinomial Naive Bayes, Logistic Regression, SVM, Random Forest
