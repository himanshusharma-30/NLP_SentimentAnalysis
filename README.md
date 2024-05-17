# Sentiment Analysis of Google Play Reviews using Natural Language Processing (NLP, Python)
This project focuses on analyzing the sentiment of user reviews from Google Play using advanced NLP techniques and the BERT model.

## Purpose
The primary aim of this project is to leverage state-of-the-art Natural Language Processing (NLP) techniques to gain meaningful insights from user reviews on Google Play. By analyzing sentiment, we can understand user feedback better, identify areas for improvement, and enhance user satisfaction for productivity apps.

##### Pipeline
##### Data Collection and Scraping
##### Data Analysis
##### Data Preprocessing
##### Models
##### API
##### Deployment

## Key Components:
1. Web scrapper: Utilized scrape_app_reviews.ipynb to scrape over 15,000 user reviews from 15 productivity apps using the google-play-scraper package.
2. Parser: Cleans and extracts the data from the raw text dump, and stores it in a csv file
3. NLP module: Build, train and save a model on a large set of reviews. This will be used for predicting the sentiments of future reviews.
   Model Evaluation:
   <img width="853" alt="image" src="https://github.com/himanshusharma-30/NLP_SentimentAnalysis/assets/118366451/a0ef3c17-e2e4-4231-b6a0-db1c7640bc3d">

5. sentiment_classifier.py to create a classifier that uses the BERT model.
6. Web application: A simple web application, that exposes an endpoint for the user to use the application.  (API deployment using FastAPI - WIP )
