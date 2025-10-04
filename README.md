# 📰 Fake News Prediction

## 📌 Overview
This project focuses on classifying **news articles as real or fake** using Natural Language Processing (NLP) techniques and a machine learning model.  
We use **TF-IDF vectorization** for feature extraction and **Logistic Regression** for classification.

---

## 📂 Dataset
The dataset consists of news articles with the following fields:

- **id** → Unique identifier for each article  
- **title** → Title of the article  
- **author** → Author of the article  
- **text** → Main content of the article (may be incomplete)  
- **label** → Target variable  
  - `0` → Real News  
  - `1` → Fake News  

---

## ⚙️ Technologies Used
- **Python 3.x**
- **NumPy, Pandas** → Data handling
- **NLTK** → Text preprocessing (stopwords & stemming)
- **Scikit-learn** →  
  - TF-IDF Vectorization  
  - Train/Test Split  
  - Logistic Regression  
  - Accuracy Evaluation

---

## 🧹 Data Preprocessing
1. **Text Cleaning** → remove punctuation, special characters, and apply stemming  
2. **Stopword Removal** → remove common words (e.g., *the, is, and*)  
3. **TF-IDF Vectorization** → convert text into numerical features  
4. **Train/Test Split** → 80% training, 20% testing (stratified by labels)  

---

## 🤖 Model Training
- **Logistic Regression** is used as the baseline classification model.  
- The model is trained on TF-IDF transformed text data.  

---

## 📊 Evaluation
- Model evaluated using **accuracy score**.  
- Achieved strong performance in distinguishing real vs fake news.  

---

## 🚀 How to Run
1. Clone this repository or download the notebook.  
2. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn nltk
