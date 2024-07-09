# Uncovering-the-Language-of-Mental-Health-Issues

# Overview
This project aims to build a model to predict whether the author of a post is at risk of suicide. The steps involved in this process are:

1. Data Preprocessing
2. Feature Generation
3. Machine Learning
4. Evaluation


# Dataset
The dataset used for this project is Suicide_Detection.csv, which contains text data and corresponding class labels (suicide or non-suicide).

# Requirements
The following Python packages are required:
pip install matplotlib pandas numpy nltk scikit-learn gensim


# Project Structure
-Suicide_Detection.csv: The dataset containing text and class labels.
-NRC Word-Emotion Association Lexicon (EmoLex) for the feature generation of Rule-based model: anger-NRC-Emotion-Lexicon.txt, anticipation-NRC-Emotion-Lexicon.txt, disgust-NRC-Emotion-Lexicon.txt, fear-NRC-Emotion-Lexicon.txt, negative-NRC-Emotion-Lexicon.txt, sadness-NRC-Emotion-Lexicon.txt: Lexicon files for rule-based model.

# Steps

1. Data Preprocessing
Import necessary packages.
Load the data.
Check for missing values.
Preprocess the text data (lowercasing, removing non-alphabets, tokenization, stemming, lemmatization).

2. Feature Generation
Generate features using Bag of Words (Binary and Frequency) and TF-IDF.

3. Machine Learning
Train and evaluate models using Naive Bayes and Random Forest classifiers.

4. Rule-based Model
Use a dictionary approach to count the occurrences of negative words.
Evaluate the rule-based model.
