# Sentiment Analysis of Google Play Reviews using Natural Language Processing (NLP, Python)
This project focuses on analyzing the sentiment of user reviews from Google Play using advanced NLP techniques and the BERT model.

## Purpose
The primary aim of this project is to leverage state-of-the-art Natural Language Processing (NLP) techniques to gain meaningful insights from user reviews on Google Play. By analyzing sentiment, we can understand user feedback better, identify areas for improvement, and enhance user satisfaction for productivity apps.

## Components of the system:
	1. Web scrapper: Responsible for scrapping the reviews on applications, and storing them in a text dump
	2. Parser: Cleans and extracts the data from the raw text dump, and stores it in a csv file
	3. NLP module: Build, train and save a model on a large set of reviews. This will be used for predicting the sentiments of future reviews.
	4. Web application: A simple web application, that exposes an endpoint for the user to use the application. 
 
##### Pipeline
##### Data Collection and Scraping
##### Data Analysis
##### Data Preprocessing
##### Models
##### API
##### Deployment

## Key Components:
#### 1. Scraping Reviews:
Utilized scrape_app_reviews.ipynb to scrape over 15,000 user reviews from 15 productivity apps using the google-play-scraper package.
Sentiment Analysis with BERT:

#### 2.Employed sentiment_analysis_with_bert_and_hugging_face_using_torch.ipynb to fine-tune the BERT base model for sentiment analysis.
Conducted necessary text preprocessing, including adding special tokens, padding, and creating attention masks.
Built a Sentiment Classifier using the Hugging Face Transformers library.
Saved the best model for deployment purposes.

#### 3. API deployment - WIP 
--- Web App created with ___FastApi.

## Technologies and Tools:

