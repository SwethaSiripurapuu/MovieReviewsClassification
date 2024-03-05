# Readme for Term Project

This project aims to perform sentiment analysis on a given dataset of text reviews using a logistic regression classifier. The dataset consists of a training set and a test set, both of which are CSV files.

The code is divided into three classes - TextPreprocessor, FeatureExtractor, and SentimentClassifier. TextPreprocessor is used to preprocess the text data by cleaning the text, removing stop words and frequent words, and lemmatizing the words. FeatureExtractor is used to extract features from the preprocessed text data using count vectorization and TF-IDF transformation. SentimentClassifier is the main class that fits the logistic regression model, predicts labels for the test data, and evaluates the performance using F1-score and confusion matrix.

The main function reads in the training and test data CSV files, preprocesses the data using TextPreprocessor, extracts features using FeatureExtractor, splits the data into training and testing sets, trains the model using SentimentClassifier, evaluates the performance, predicts the labels for the test data, and writes the predicted labels to a CSV file.

To run the code, make sure the necessary libraries like pandas, numpy, scikit-learn, re, and nltk are installed. Then, simply run the main() function.

Note: Before running the code, ensure that the CSV files are in the correct format, and the paths to the CSV files are correctly specified.
