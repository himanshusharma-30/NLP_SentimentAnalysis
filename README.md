# Sentiment Analysis of Google Play Reviews using Natural Language Processing (NLP, Python)
This project focuses on analyzing the sentiment of user reviews from Google Play using advanced NLP techniques and the BERT model.

## Purpose
The primary aim of this project is to leverage state-of-the-art Natural Language Processing (NLP) techniques to gain meaningful insights from user reviews on Google Play. By analyzing sentiment, we can understand user feedback better, identify areas for improvement, and enhance user satisfaction for productivity apps.

## Key Components:
Scraping Reviews:

Utilized scrape_app_reviews.ipynb to scrape over 15,000 user reviews from 15 productivity apps using the google-play-scraper package.
Sentiment Analysis with BERT:

Employed sentiment_analysis_with_bert_and_hugging_face_using_torch.ipynb to fine-tune the BERT base model for sentiment analysis.
Conducted necessary text preprocessing, including adding special tokens, padding, and creating attention masks.
Built a Sentiment Classifier using the Hugging Face Transformers library.
Saved the best model for deployment purposes.

## Technologies and Tools:
Python
BERT (Bidirectional Encoder Representations from Transformers)
Hugging Face Transformers library
google-play-scraper package
Jupyter Notebooks
