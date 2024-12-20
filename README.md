# sms-spam

The **`sms-spam-classifier.ipynb`** file contains the code for training a machine learning model to classify text messages as either spam or not spam. It outlines the entire pipeline for preprocessing text data, transforming it into numerical features using a Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer, and training the model. 

This file saves the trained model and vectorizer as **`model.pkl`** and **`vectorizer.pkl`**. 

The **`app.py`** file is the main application script built with Streamlit, to provide an interactive web-based interface for the spam classification model.

To run this application, the pre-trained **`model.pkl`** and **`vectorizer.pkl`** files are required, as they contain the necessary resources for predictions.
