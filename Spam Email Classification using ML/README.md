# Spam Mail Classification using Machine Learning

This project aims to build a machine learning model to classify emails as spam or not spam using natural language processing (NLP) techniques.

## Problem

Spam emails clutter inboxes and pose security threats. The goal was to create a model that could automatically detect and classify emails based on their content.

## Dataset

- `spam.csv`: ~5,500 labeled email messages with labels `spam` and `ham`.

##Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- TF-IDF Vectorizer
- Naive Bayes, SVM, Logistic Regression

## Approach

1. **Data Cleaning:** Removed punctuation, lowercased text, removed stopwords.
2. **Vectorization:** Converted text using TF-IDF.
3. **Modeling:** Trained Naive Bayes, SVM, and Logistic Regression.
4. **Evaluation:** Used accuracy, precision, and recall to evaluate performance.

## Results

- **Best Model:** Naive Bayes
- **Accuracy:** ~98%
- Lightweight and fast, suitable for real-time email classification.

## Files

- `Spam Mail Classification using ML.ipynb`: The full notebook.
- `spam.csv`: Dataset used in this project.

## 🙋‍♂️ Author

- Muhammad Waqas Khan
- Aspiring Data Scientist | Python & AI Enthusiast
