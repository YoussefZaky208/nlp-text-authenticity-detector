NLP Text Authenticity Detector
Binary NLP classifier to detect AI-generated vs. human-written text.
Overview
Built using a 1,464-sample Kaggle dataset, this project classifies text as either human-written or AI-generated using classical NLP and machine learning techniques.
Approach

Preprocessing: lowercasing, punctuation/URL removal, tokenization, stopword removal, lemmatization
Feature extraction: Bag-of-Words (CountVectorizer)
Models: Multinomial Naive Bayes, Logistic Regression

Results
Both models achieved 99.32% accuracy on 292 unseen test samples, correctly classifying 275/275 human-written and 15/17 AI-generated texts.
Files

NLP_Project.ipynb — full implementation
NLP_Project_Report.pdf — project report

Dataset
AI vs Human Text Dataset — Kaggle
