# 📧 Spam Mail Detection using Logistic Regression

This project uses a Supervised Machine Learning approach to classify email messages as Spam or Ham (Not Spam). Text data is transformed into numerical features using TF-IDF Vectorizer, and a Logistic Regression model is trained for binary classification.

<p align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdzRsaWdwanIxbmN4enhiNHdxNjV1NGlkN3V5ajRhams5NHZibndzeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JRPYrblGdODA5MF7eg/giphy.gif" alt="Spam Mail Detection Animation" width="600"/>
</p>

# 🚀 Project Overview
Goal: Predict whether an email message is spam or ham.
  
 1. Model Used: Logistic Regression
  
 2. Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency)
  
 3. Accuracy:
  
⭐Training Accuracy: 96%
  
⭐Testing Accuracy: 95%

# 🧠 Machine Learning Pipeline
  Data Loading
  
 1. Dataset includes messages and their labels.
  
 2. Preprocessing
  
    Optional steps like removing punctuation, converting to lowercase, and removing stop words.
  
 3. Feature Extraction
  
    TfidfVectorizer is used to convert text messages into numerical feature vectors.
  
 4. Model Training
  
    A Logistic Regression classifier is trained on the vectorized data.
  
 5. Evaluation
  
    Accuracy is measured on both training and testing datasets.

# 🛠 Technologies Used
  1.Python
  
  2.Pandas
  
  3.Scikit-learn
  
  4.TfidfVectorizer

  5.Google Collab  

# 📚 Future Enhancements
  1.Experiment with other models: Naive Bayes, SVM, Random Forest
  
  2.Integrate additional NLP steps (stemming, lemmatization)
  
  3.Build a web-based input form for live prediction
  
  4.Extend to real-time email inbox scanning

