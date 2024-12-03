### IMDB-Sentiment-Analysis-with-Simple-RNN

# Overview
This project involves building a text classification model using the IMDB dataset. The goal is to classify movie reviews as either positive or negative. A Simple Recurrent Neural Network (Simple RNN) is implemented for sentiment analysis to understand the temporal structure of the text data.

# Dataset
The IMDB dataset is a widely used benchmark dataset for binary sentiment classification tasks. It consists of 50,000 movie reviews split equally into training and testing sets. Each review is labeled as either positive or negative.

# Key Features of the Project
1.Text Preprocessing:
Tokenization of text data.
Padding and truncating reviews to ensure uniform input lengths.
Conversion of words to numerical sequences using a vocabulary dictionary.
2. Model Architecture:
A Simple RNN is used to capture sequential dependencies in the text.
Additional layers such as Embedding, Dense, and Dropout are added to improve performance.
3.Training and Validation:
The model is trained using the training data and evaluated on the test set.
Metrics such as accuracy and loss are used for evaluation.
4. Hyperparameter Tuning:
Learning rate, batch size, and RNN units are optimized for better performance.

# Dependencies
The following libraries are required to run the project:
Python 3.10.11
tensorflow==2.15.0
pandas 
numpy 
scikit-learn
tensorboard
matplotlib
streamlit
scikeras
