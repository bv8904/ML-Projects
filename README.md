📧 Spam Mail Detection using Logistic Regression

This project uses a Supervised Machine Learning approach to classify email messages as Spam or Ham (Not Spam). Text data is transformed into numerical features using TF-IDF Vectorizer, and a Logistic Regression model is trained for binary classification.

<p align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdzRsaWdwanIxbmN4enhiNHdxNjV1NGlkN3V5ajRhams5NHZibndzeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JRPYrblGdODA5MF7eg/giphy.gif" alt="Spam Mail Detection Animation" width="600"/>
</p>

🚀 Project Overview
Goal: Predict whether an email message is spam or ham.
  
  Model Used: Logistic Regression
  
  Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency)
  
  Accuracy:
  
  Training Accuracy: 96%
  
  Testing Accuracy: 95%

🧠 Machine Learning Pipeline
  Data Loading
  
  Dataset includes messages and their labels.
  
  Preprocessing
  
  Optional steps like removing punctuation, converting to lowercase, and removing stop words.
  
  Feature Extraction
  
  TfidfVectorizer is used to convert text messages into numerical feature vectors.
  
  Model Training
  
  A Logistic Regression classifier is trained on the vectorized data.
  
  Evaluation
  
  Accuracy is measured on both training and testing datasets.

🛠 Technologies Used
  Python
  
  Pandas
  
  Scikit-learn
  
  TfidfVectorizer
  
  Jupyter Notebook / Google Colab

📚 Future Enhancements
  Experiment with other models: Naive Bayes, SVM, Random Forest
  
  Integrate additional NLP steps (stemming, lemmatization)
  
  Build a web-based input form for live prediction
  
  Extend to real-time email inbox scanning

