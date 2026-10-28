NLP Movie Review Sentiment Analysis API


Description

A REST API developed in Python (Flask) that serves a Machine Learning model for sentiment analysis on movie reviews. The application cleans raw text, vectorizes it using TF-IDF, and predicts whether the review is positive or negative.

Technologies

• Backend: Python, Flask, Flask-CORS
• Machine Learning: Scikit-Learn (Joblib), NLTK
• Text Processing: Regex (Regular Expressions)

Features

• NLP preprocessing pipeline (lowercasing, HTML tag removal, punctuation removal, whitespace normalization).
• Inference using serialized ML models (sentiment_model.pkl and tfidf_vectorizer.pkl).
• /predict API endpoint processing JSON requests in real-time.
• Returns binary prediction, text label, and confidence probability.

Installation and Setup

1. Clone the repository and install dependencies (requires flask, flask-cors, joblib, scikit-learn):bash
pip install -r requirements.txt
