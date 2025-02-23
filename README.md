# Spam Classifier using NLP

## Overview
This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify messages as **spam** or **ham (not spam).** The model learns from textual data and predicts whether a given message is spam based on its content.

## Features
- **Data Preprocessing:**  
  - Text cleaning: Removing punctuation, special characters, and stop words.  
  - Tokenization and lemmatization for text normalization.  
  - Converting text into numerical representations using **TF-IDF**.  

- **Machine Learning Models Used:**  
  - Logistic Regression  
  - Naïve Bayes (MultinomialNB)  
  - Support Vector Machine (SVM)  
  - Random Forest Classifier  

- **Performance Evaluation:**  
  - Accuracy, Precision, Recall, and F1-score used to assess classification performance.  
  - ROC-AUC score to evaluate model discrimination ability.  

## Dataset
The dataset consists of SMS/email messages labeled as:
- **Spam (1)** – Unwanted or promotional messages.  
- **Ham (0)** – Legitimate, non-spam messages.  

## Dependencies
Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn nltk scikit-learn
