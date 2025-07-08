# Video Game Reviews Sentiment Analysis

This project analyzes video game reviews from Amazon to perform sentiment analysis and classify reviews as positive or negative.

## Project Description

The project includes:
- Data loading and preprocessing from a compressed JSON file
- Exploratory data analysis with visualizations
- Text preprocessing including tokenization, lemmatization, and stopword removal
- Topic modeling using LDA
- Sentiment classification using Random Forest with TF-IDF features

## Key Features

- Word clouds for positive and negative reviews
- Bigram analysis for different rating categories
- Topic modeling for negative reviews
- Binary classification (positive/negative) with accuracy metrics

## Installation

1. Clone this repository
2. Install the required packages:
3. Download NLTK data:
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_treebank_pos_tagger')
