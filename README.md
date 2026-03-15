# Twitter Sentiment Analysis

## Project Overview
This project focuses on performing **Sentiment Analysis on Twitter data** using **Natural Language Processing (NLP) and Machine Learning**. The goal is to analyze tweets and classify their sentiment as **Positive, Negative, or Neutral**.

Sentiment analysis helps businesses and organizations understand **public opinion, customer feedback, and social media trends**.

---

## Dataset
The dataset used in this project is:

Twitter_Data.csv

It contains Twitter posts and their corresponding sentiment labels.

### Dataset Columns

clean_text – Tweet text data  
category – Sentiment label  

Sentiment Labels:

- **1 → Positive**
- **0 → Neutral**
- **-1 → Negative**

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Workflow

### 1. Data Loading
The dataset was loaded using Pandas.

### 2. Data Cleaning
- Removed missing values
- Converted text to lowercase
- Removed stopwords

### 3. Feature Engineering
Text data was converted into numerical features using **TF-IDF Vectorization**.

### 4. Model Building
A **Multinomial Naive Bayes** machine learning model was used for sentiment classification.

### 5. Model Evaluation
The model performance was evaluated using:

- Accuracy Score
- Classification Report

### 6. Data Visualization
Visualizations were created to show:

- Sentiment distribution
- Most frequent words in tweets

---

## Results

The sentiment analysis model successfully classified tweets into:

- Positive
- Neutral
- Negative

The model achieved good accuracy in predicting tweet sentiment.

---

## Project Files

Twitter_Data.csv – Original dataset  
Twitter_Sentiment_Analysis.ipynb – Project notebook  
sentiment_model.pkl – Trained machine learning model  
README.md – Project documentation  

---

## Future Improvements

- Use deep learning models such as LSTM or BERT
- Improve text preprocessing
- Deploy the model as a web application
