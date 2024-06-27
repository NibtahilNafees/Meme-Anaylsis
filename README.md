# Meme-Anaylsis
# Meme Sentiment Classification Project

This repository contains code for developing a sentiment classification model for Internet memes. The project involves training multiple classifiers for both text and image data.

## Project Overview

The goal of this project is to classify memes based on their sentiment. Given an Internet meme, the task is to classify it as positive, very positive, negative, very negative, or neutral. The project involves training six classifiers (three for images and three for text) and using majority voting to determine the final sentiment label. A Flask web application is also created for user interaction with the model.

## Dataset

The dataset includes a collection of memes with both image and text components. The text data contains sentiment labels which are used to train and evaluate the classifiers.
Here's the link for the dataset "https://drive.google.com/file/d/1J1SknxcjbjuK0I3OksEleQ7nF53cxdWS/view?usp=share_link".

## Preprocessing

### Text Data
- Correcting and filling in missing text data.
- Removing stopwords.
- Merging sentiment classes into positive, neutral, and negative.
- Transforming text data using TF-IDF.

### Image Data
- Resizing images.
- Flattening image arrays.

## Classifiers

### Text Classifiers
1. Random Forest Classifier
2. Decision Tree Classifier
3. Logistic Regression

### Image Classifiers
1. K-Neighbors Classifier
2. Support Vector Classifier (SVC)
3. Gaussian Naive Bayes

## Results

The performance of each classifier is evaluated using a confusion matrix, accuracy, recall, precision, and F1-score. Majority voting is used to determine the final sentiment label.

