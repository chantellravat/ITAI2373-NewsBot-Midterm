# ITAI 2373 Midterm Project: NewsBot Intelligence System

## Project Overview
The NewsBot Intelligence System uses Natural Language Processing (NLP) and machine learning to analyze news articles, identify patterns in language, and classify articles into news categories.

## Business Problem
News organizations receive large amounts of news content every day. Manually organizing articles takes time. An automated system can help categorize articles, analyze sentiment, identify important entities, and support faster content organization.

## Dataset
This project uses the BBC News Classification dataset, containing news articles in five categories:
- Business
- Entertainment
- Politics
- Sport
- Tech

The dataset was cleaned by checking for duplicate articles and preparing text for analysis.

## Methods and Technologies
The project applies:
- Text preprocessing, tokenization, stemming, and lemmatization
- TF-IDF feature extraction and category keyword analysis
- Part-of-speech tagging and dependency parsing
- Sentiment and emotion analysis
- Named Entity Recognition (NER)
- Machine learning classification using Logistic Regression and Multinomial Naive Bayes
- Hyperparameter tuning and model evaluation

**Tools:** Python, Google Colab, pandas, scikit-learn, NLTK, spaCy, and VADER Sentiment Analysis.

## Evaluation
The project compares classification models and evaluates their performance using classification metrics, a confusion matrix, and error analysis. It also explores linguistic patterns, sentiment, emotions, and named entities across news categories.

## Limitations
Automated sentiment, emotion, and entity extraction may not fully understand context, sarcasm, or ambiguous language. Model performance also depends on the dataset and preprocessing choices.

## Conclusion
This project demonstrates how NLP and machine learning can support news classification and text analysis. The results can help inform the development of automated tools for organizing and understanding news content.

## How to Run
Open `NewsBot_Midterm.ipynb` in Google Colab or Jupyter Notebook and run the notebook cells in order. Install any required libraries and upload or load the dataset when prompted.

## Contributions
This repository contains the project notebook and analysis. Add the names of all group members and describe each member's contributions here before final submission.
