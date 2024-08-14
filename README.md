# SMS Spam Classifier

This project is an ML-based SMS Spam Classifier that identifies whether an SMS message is spam or not-spam. The model is built using techniques like TF-IDF for feature extraction and classifiers like Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) for prediction.

## Project Structure

- **notebooks/**: Contains Jupyter Notebooks used for initial data exploration, feature extraction, and model training.
- **app.py**: The main application file developed in PyCharm, which loads the pre-trained model and vectorizer to classify SMS messages.
- **model.pkl**: The serialized trained model file.
- **vectorized.pkl**: The serialized TF-IDF vectorizer file.
- **data/**: Contains the dataset used for training and testing the model.
- **requirements.txt**: List of Python packages required to run the project.

## Features

- **TF-IDF Vectorization**: The model uses Term Frequency-Inverse Document Frequency (TF-IDF) to convert SMS messages into a numerical format suitable for machine learning.
- **Classification Algorithms**: Multiple classification algorithms are implemented, including:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machines (SVM)
- **Model Serialization**: The trained model and vectorizer are saved using `pickle` for easy deployment.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sms-spam-classifier.git
   cd sms-spam-classifier

##  Create a virtual environment and activate it

python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

## Install the required dependencie

pip install -r requirements.txt

## Run the app.py file

python app.py

