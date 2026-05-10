# Artificial_Neural_Network_for_Text_Classification
ANN Text Classification using Deep Learning

A complete Natural Language Processing (NLP) project that performs text classification using an Artificial Neural Network (ANN) with TensorFlow and Keras.

Project Overview

This project demonstrates how to build a deep learning model for text classification using a CSV dataset containing news titles and descriptions.

The workflow includes:

Data loading
Text preprocessing
Tokenization
Sequence padding
ANN model building
Model training
Performance evaluation

The model learns to classify text into multiple categories using neural networks.

Dataset Information

Dataset contains:

Column Name	                 Description
Title                   	News headline/title
Description             	News article description
Class Index	              Target category label

The Title and Description columns are combined into a single text feature for training.

Technologies Used
Python
Pandas
NumPy
TensorFlow / Keras
Scikit-learn
NLTK
Matplotlib
Project Workflow
1. Data Loading
Load CSV dataset using Pandas.
2. Text Preprocessing
Convert text to lowercase
Remove special characters
Remove stopwords
Lemmatization
3. Text Vectorization
Tokenization
Convert words into numerical sequences
Padding sequences
4. ANN Model Building
Embedding Layer
Dense Neural Network Layers
Dropout for regularization
Softmax output layer
5. Model Training
Train-test split
Model fitting using TensorFlow/Keras
6. Model Evaluation
Accuracy score
Classification report
Training vs validation accuracy graph
