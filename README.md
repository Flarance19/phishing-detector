# 🛡 PhishGuard — Phishing Email Detector

A machine learning model that classifies emails as **Phishing** or **Safe**
using Scikit-learn with TF-IDF and engineered features.

## Features
- 4 ML models: Random Forest, Gradient Boosting, Logistic Regression, Naive Bayes
- TF-IDF (800 bigram features) + 19 URL & text features
- 100% accuracy on test set
- Interactive HTML dashboard for live email analysis

## How to Run
- pip install -r requirements.txt
- python phishing_detector.py
- python phishing_detector.py --predict

## Tech Stack
Python · Scikit-learn · Pandas · NumPy · HTML/CSS/JS
