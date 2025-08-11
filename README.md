# Sarcasm-Detector
This project uses Natural Language Processing (NLP) and Machine Learning algorithms to detect sarcasm in headlines.
The dataset contains labeled headlines (is_sarcastic: 0 or 1), which are preprocessed, vectorized, and then classified using multiple models to compare performance.

Key Features
Data Preprocessing:
Lowercasing, punctuation removal, stopword removal, lemmatization.
Tokenization using NLTK.
Vectorization:
TF-IDF (Term Frequency–Inverse Document Frequency) to convert text into numerical features.

Models Implemented:
Naive Bayes (MultinomialNB)
Support Vector Machine (LinearSVC)
K-Nearest Neighbors (KNN)

Evaluation:
Accuracy, precision, recall, and F1-score comparison.
Results table summarizing each model’s performance.
Workflow
Load and preprocess dataset.
Convert text into TF-IDF feature vectors.
Train multiple classifiers on the training set.
Test on unseen data and evaluate performance.
Compare results to select the best-performing model.

Use Case
Sarcasm detection can be useful for improving sentiment analysis systems, moderating online comments, and understanding the tone in social media content.

