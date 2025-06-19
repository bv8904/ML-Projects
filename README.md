📧 Spam Mail Detection using Logistic Regression

This project uses a Supervised Machine Learning approach to classify email messages as Spam or Ham (Not Spam). Text data is transformed into numerical features using TF-IDF Vectorizer, and a Logistic Regression model is trained for binary classification.

🚀 Project Overview
	•	Goal: Predict whether an email message is spam or ham.
	•	Model Used: Logistic Regression
	•	Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency)
	•	Accuracy:
	•	Training Accuracy: 96%
	•	Testing Accuracy: 95%

⸻

🧠 Machine Learning Pipeline
	1.	Data Loading:
	•	Dataset includes messages and their labels.
	2.	Preprocessing:
	•	Optional steps like removing punctuation, converting to lowercase, and removing stop words.
	3.	Feature Extraction:
	•	TfidfVectorizer is used to convert text messages into numerical feature vectors.
	4.	Model Training:
	•	A Logistic Regression classifier is trained on the vectorized data.
	5.	Evaluation:
	•	Accuracy is measured on both training and testing datasets.

⸻

🛠 Technologies Used
	•	Python
	•	Pandas
	•	Scikit-learn
	•	TfidfVectorizer
	•	Jupyter Notebook / Google Colab

📚 Future Enhancements
	•	Experiment with other models: Naive Bayes, SVM, Random Forest
	•	Integrate additional NLP steps (stemming, lemmatization)
	•	Build a web-based input form for live prediction
	•	Extend to real-time email inbox scanning
