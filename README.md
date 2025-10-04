📰 Fake News Prediction
📌 Overview

This project focuses on classifying news articles as real or fake using Natural Language Processing (NLP) techniques and a machine learning model.
We use TF-IDF vectorization for feature extraction and Logistic Regression for classification.

📂 Dataset

The dataset consists of news articles with the following fields:

id → Unique identifier for each article

title → Title of the article

author → Author of the article

text → Main content of the article (may be incomplete)

label → Target variable

0 → Real News

1 → Fake News

⚙️ Technologies Used

Python 3.x

NumPy, Pandas → Data handling

NLTK → Text preprocessing (stopwords & stemming)

Scikit-learn →

TF-IDF Vectorization

Train/Test Split

Logistic Regression

Accuracy Evaluation

🧹 Data Preprocessing

Text Cleaning → remove punctuation, special characters, and apply stemming

Stopword Removal → remove common words (e.g., the, is, and)

TF-IDF Vectorization → convert text into numerical features

Train/Test Split → 80% training, 20% testing (stratified by labels)

🤖 Model Training

Logistic Regression is used as the baseline classification model.

The model is trained on TF-IDF transformed text data.

📊 Evaluation

Model evaluated using accuracy score.

Achieved strong performance in distinguishing real vs fake news.

🚀 How to Run

Clone this repository or download the notebook.

Install dependencies:

pip install numpy pandas scikit-learn nltk


Download NLTK stopwords:

import nltk
nltk.download('stopwords')


Run the Jupyter Notebook:

jupyter notebook Project_5_Fake_News_Prediction.ipynb

📌 Future Improvements

Experiment with Random Forest, XGBoost, or Deep Learning models (LSTM, Transformers)

Replace stemming with lemmatization

Perform hyperparameter tuning for better accuracy

Deploy as a web app using Flask/Streamlit for real-time predictions