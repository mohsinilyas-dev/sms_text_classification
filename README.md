SMS Spam Detection Model
A TensorFlow-based project that uses a bidirectional LSTM model to classify SMS messages as either "ham" or "spam".

Overview
This project aims to develop a machine learning model that can accurately classify SMS messages as either legitimate ("ham") or spam. The model is trained on a dataset of labeled SMS messages and uses a bidirectional LSTM architecture to learn features and make predictions.

Features
Bidirectional LSTM model: The model uses a bidirectional LSTM architecture to learn features from the SMS messages.
TensorFlow implementation: The model is implemented using TensorFlow, a popular open-source machine learning library.
High accuracy: The model achieves an accuracy of 0.85 on the validation set.
Detailed implementation: The repository includes a detailed implementation of the model, including data preprocessing, model training, and testing.
Testing framework: The repository includes a testing framework to evaluate the model's performance on a set of test messages.
Usage
To use the model, simply clone the repository and run the predict_message function with a test message. The function will return a prediction of whether the message is "ham" or "spam".

Requirements
TensorFlow: The model requires TensorFlow 2.4.0 or later.
Python: The model requires Python 3.7.10 or later.
NumPy: The model requires NumPy 1.19.5 or later.
Pandas: The model requires Pandas 1.2.4 or later.
Dataset
The model is trained on a dataset of labeled SMS messages, which is included in the repository. The dataset consists of two files: train-data.tsv and valid-data.tsv.


Contributing
Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.
