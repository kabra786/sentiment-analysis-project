# sentiment-analysis-project
# Comparative Sentiment Analysis using Bag of Words and TF-IDF

## Project Overview

This project performs sentiment analysis on movie reviews using Natural Language Processing (NLP) techniques. Two feature extraction methods, Bag of Words (BoW) and TF-IDF, are compared using Logistic Regression.

## Dataset Description

Dataset Used: NLTK Movie Reviews Corpus

- Total Reviews: 2000
- Positive Reviews: 1000
- Negative Reviews: 1000

## Installation

Install required libraries:

```bash
pip install -r requirements.txt
```

## Methodology

### Preprocessing
- Lowercasing
- Punctuation Removal
- Special Character Removal
- Tokenization
- Stop Word Removal
- Lemmatization

### Feature Extraction
- Bag of Words (BoW)
- TF-IDF

### Classification Model
- Logistic Regression

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results Summary

Both models were evaluated and compared. TF-IDF achieved slightly better performance because it assigns higher importance to informative words and reduces the impact of common words.

## Screenshots

Screenshots are available in the results folder.

## Project Structure

sentiment_analysis_project/
├── data/
├── src/
├── notebooks/
├── results/
├── README.md
├── requirements.txt
└── .gitignore

## Author

Kabrah Anwaar
