# BARBIE_REVIEW_SENTIMENT_ANALYSIS
![Landing Page](https://github.com/arundhutiacad/BARBIE_REVIEW_SENTIMENT_ANALYSIS/blob/main/Barbie.jpg)




GitHub Repository Description - Barbie Review Sentiment Analysis using Scraped IMDb Data with TextBlob, Flair, and VADER Models

Introduction:
This GitHub repository aims to perform sentiment analysis on Barbie movie reviews scraped from the IMDb website. The sentiment analysis is conducted using three different natural language processing (NLP) models: TextBlob, Flair, and VADER. The objective is to analyze the sentiment polarity (positive, negative, or neutral) of the reviews and determine which model provides the most accurate predictions for Barbie movie sentiments.

Dataset:
The dataset used in this project consists of user reviews for Barbie movies. The data is scraped from the IMDb website, containing text-based reviews along with their corresponding ratings.

Methods:
1. Data Collection and Preprocessing:
   - Scrape user reviews and ratings for Barbie movies from IMDb using web scraping techniques.
   - Preprocess the text data by removing special characters, stopwords, and performing text normalization.

2. Sentiment Analysis Models:
   a. TextBlob:
      - Utilize the TextBlob library for sentiment analysis.
      - Train a sentiment classifier using the TextBlob API on the preprocessed data.
      - Predict sentiment polarity for each review.

   b. Flair:
      - Utilize the Flair library, which employs pre-trained transformer models for NLP tasks.
      - Fine-tune the Flair transformer model on the preprocessed data for sentiment analysis.
      - Predict sentiment polarity for each review.

   c. VADER (Valence Aware Dictionary and sEntiment Reasoner):
      - Use the VADER lexicon-based sentiment analysis model.
      - Analyze the sentiment of each review using the VADER model.

3. Model Evaluation:
   - Compare the performance of the TextBlob, Flair, and VADER models.
   - Calculate evaluation metrics such as accuracy, precision, recall, and F1-score to measure each model's performance.

4. Results and Comparison:
   - Analyze the results to determine which model provides the most accurate sentiment predictions for Barbie movie reviews.
   - Visualize the model performance using graphs or charts for better understanding.

Conclusion:
The GitHub repository showcases the sentiment analysis process for Barbie movie reviews using three different NLP models: TextBlob, Flair, and VADER. The repository provides code, documentation, and data necessary to reproduce the analysis and results. The comparison between the models will help identify the most effective model for predicting sentiments accurately, providing insights into the sentiment of the audience towards Barbie movies. Developers and NLP enthusiasts can use this repository as a reference for similar sentiment analysis projects or for exploring different NLP models for sentiment classification.
