# Spam Detection Machine Learning Model
<img width="1439" alt="Screenshot 2023-03-27 at 2 20 33 PM" src="https://user-images.githubusercontent.com/64217477/227893960-1e63a8be-c06d-4957-8062-54252d4daae5.png">

This repository contains code for a spam detection machine learning model trained on a dataset from Kaggle. The model is built using the Naive Bayes algorithm and several other models have been tried and tested to get the best results while detecting spam.

## Dataset

The dataset used for training the model is taken from Kaggle and contains emails labeled as spam or not spam. The dataset can be found at this link: [Kaggle Spam Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

## Model

The model is built using the Naive Bayes algorithm. Naive Bayes is a simple probabilistic classifier that is based on Bayes' theorem. It assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature. Despite this assumption, Naive Bayes has been shown to be very effective in many real-world situations, including spam detection.

## Web App

A web app has been created using Streamlit to demonstrate the spam detection model. The web app allows users to enter an email message and the model will predict whether the email is spam or not. To run the web app, navigate to the `app/` directory and run the following command:

streamlit run app.py

This will start the web app and it can be accessed in a web browser at `http://localhost:8501`.

## Conclusion
This spam detection machine learning model and web app can be used to effectively detect spam emails. The Naive Bayes algorithm has been shown to be effective in this task, and the web app provides a user-friendly interface for using the model.
