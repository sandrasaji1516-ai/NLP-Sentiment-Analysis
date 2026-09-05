# NLP-Based Sentiment Analysis of Movie Reviews

## Project Overview

This project focuses on classifying movie reviews into two sentiment categories: Positive and Negative.

The project uses Natural Language Processing (NLP) techniques with TF-IDF feature extraction and Logistic Regression for sentiment classification.

## Dataset

- Dataset: IMDb Dataset of 50K Movie Reviews
- Number of Reviews: 50,000
- Classes: Positive and Negative
- Features: Review, Sentiment
- Training Data: 40,000 reviews
- Testing Data: 10,000 reviews

## Methodology

1. Data Collection
2. Data Cleaning
3. Train-Test Split
4. TF-IDF Feature Extraction
5. Logistic Regression Model
6. Sentiment Prediction
7. Model Evaluation

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Model

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert the movie review text into numerical features.

### Logistic Regression

Logistic Regression is used to classify the reviews into Positive and Negative sentiment categories.

## Results

The model achieved an accuracy of **88.98%** on the test dataset.

- Negative F1-score: 0.89
- Positive F1-score: 0.89
- Weighted Average F1-score: 0.89

## Project Files

- `sentiment_analysis.py` – Python source code
- `requirements.txt` – Required Python libraries
- `NLP_Sentiment_Analysis_Report.pdf` – Project report
- `IMDB Dataset.csv` – Dataset used for the project

## Conclusion

The project successfully demonstrates sentiment analysis of movie reviews using NLP, TF-IDF, and Logistic Regression. The model provides good performance for binary sentiment classification.
