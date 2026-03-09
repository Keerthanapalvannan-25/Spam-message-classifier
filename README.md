# Spam Message Classifier

## Project Overview
This project is a Natural Language Processing (NLP) based text classification system that automatically detects whether a message is **Spam** or **Ham (Normal message)**. The model analyzes the content of text messages and predicts if the message is unwanted spam.

Handling text data requires converting unstructured text into numerical form before applying machine learning algorithms. This project demonstrates the process of cleaning text data, transforming messages into numerical vectors, training a classification model, and evaluating its performance.

## Key Highlights
* **Data Preprocessing:** Cleaned the dataset, removed unnecessary columns, and converted message labels (ham/spam) into numerical format for model training.
* **Feature Engineering:** Applied **TF-IDF (Term Frequency–Inverse Document Frequency)** vectorization to convert text messages into meaningful numerical feature vectors.
* **Model Training:** Implemented a **Multinomial Naive Bayes** classifier to identify spam messages based on the importance of words in each message.
* **Model Evaluation:** Evaluated the model using **accuracy score, confusion matrix, and classification report** to measure classification performance.
* **Prediction System:** Built a function that allows users to input any message and instantly classify it as **Spam or Ham**.

## Tech Stack
* **Language:** Python  
* **Data Manipulation:** Pandas, NumPy  
* **Natural Language Processing:** Scikit-Learn TF-IDF Vectorizer  
* **Machine Learning Algorithm:** Multinomial Naive Bayes  
* **Model Evaluation:** Scikit-Learn (Accuracy, Confusion Matrix, Classification Report)
