# Sentiment_Analysis_on_socical_media_comments

# Project Description

## Skills Utilized
- Python
- Numpy
- Pandas
- Naive Bayes Classifier
- Natural Language Processing (NLP)
- NLTK (Natural Language Toolkit)

## Overview
This project involved the analysis of social media text data to determine sentiment (positive or negative) using machine learning techniques. The dataset was sourced from Kaggle and comprised columns for social media content and sentiment labels. The primary objective was to classify text data into their respective sentiment categories.

## Feature Engineering
During feature engineering, an additional column representing the polarity score of each tweet was created. This score was calculated as the difference between the positive and negative scores of the text. Exploratory data analysis revealed a significant relationship between text polarity and sentiment.

## Text Data Preprocessing
Text data preprocessing steps included normalization, stemming, and lemmatization to standardize the text format. Punctuation and stopwords were removed, and the text corpus was transformed using TF-IDF Vectorizer with consideration for bigrams and trigrams. A maximum of 10,000 features were selected for the vectorization process.

## Model Training and Evaluation
A Naive Bayes Classifier model was trained on the preprocessed data. Hyperparameter tuning was conducted using GridSearchCV to optimize model performance. The trained model was evaluated on a separate test dataset, achieving an approximate accuracy of 85%.
