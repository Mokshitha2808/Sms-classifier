# Sms-classifier

This project involves building a classifier to identify SMS messages as spam or ham (non-spam). The project includes text preprocessing, feature extraction, and the implementation and comparison of three different machine learning models: Naive Bayes, Support Vector Classifier (SVC), and Logistic Regression.

## Table of Contents:
• Introduction    
• Dataset     
• Requirements for installation     
• Usage       
• Preprocessing      
• Feature Extraction      
• Models       
• Evaluation        
• Results         

## Introduction:
The goal of this project is to classify SMS messages as spam or ham. The project includes preprocessing the text data, extracting features using the NLTK library, and building and evaluating three machine learning models.

## Dataset:
The dataset used for this project consists of labeled SMS messages. Each message is labeled as either "spam" or "ham".

## Requirements:
Python 3.x      
NLTK  
Scikit-learn  
Pandas  
NumPy  

## Usage:
1) Clone the repository:    
      git clone https://github.com/yourusername/sms-classifier.git  
2) Navigate to the project directory:  
      cd sms-classifier  
3) Run the main script:  
      python main.py  

## Preprocessing:
The preprocessing steps involve:

• Tokenizing the text  
• Converting to lowercase  
• Removing stop words  
• Stemming
These steps are implemented using the NLTK library.

## Feauture Extraction:
Features are extracted using the technique:  
• Term Frequency-Inverse Document Frequency (TF-IDF)  

## Models:
Three models are implemented and compared:

1) Naive Bayes  
2) Support Vector Classifier (SVC)  
3) Logistic Regression  

## Evaluation:
The models are evaluated based on the following metrics:

Accuracy  
Precision  
Recall  
F1 Score  

## Results:
The performance of each model is compared and the results are presented.
Got good accuracy for multinomial naive bayes and SVC.

