# IMDB Sentiment Analysis using RNN and NLP

## Overview
This project performs sentiment analysis on IMDB movie reviews using Natural Language Processing (NLP) and a Recurrent Neural Network (RNN) built with PyTorch. The model classifies movie reviews as Positive or Negative based on textual data.

## Features
- Text preprocessing using NLTK
- URL removal
- HTML tag removal
- Punctuation cleaning
- Stopword removal
- Porter Stemming
- TF-IDF vectorization
- RNN-based sentiment classification
- Model training and evaluation using PyTorch

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- PyTorch
- Jupyter Notebook

## Dataset
- IMDB Movie Review Dataset
- Binary sentiment classification:
  - Positive
  - Negative

## Project Workflow

### 1. Text Preprocessing
- Remove URLs
- Remove HTML tags
- Remove punctuations
- Remove stopwords
- Apply stemming

### 2. Feature Extraction
- TF-IDF Vectorization (`max_features=5000`)

### 3. Model Building
- Recurrent Neural Network (RNN)
- Fully Connected Layer
- Sigmoid Activation
- Binary Cross Entropy Loss
- Adam Optimizer

### 4. Evaluation
- Accuracy calculation on test data

### Model Architecture

Input Layer → RNN Layer → Fully Connected Layer → Sigmoid Activation

## Author
Subhajit Jana
B.Tech CSE (AI & ML)
The Neotia University
