# 🧪 Diabetes Prediction using Machine Learning

<p align="center">
  <img src="https://i.makeagif.com/media/6-19-2024/vOhDPv.gif" alt="Diabetes Prediction" width="600"/>
</p>

This project focuses on predicting whether a patient is likely to have diabetes based on various health-related metrics. It uses a supervised machine learning approach with classification algorithms.

---

## 📂 Dataset

- *Source*: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- *Features*:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- *Target*: Outcome (1 = Diabetic, 0 = Non-Diabetic)

---

## 🧠 ML Pipeline

1. *Data Preprocessing*:
   - Handling missing or zero values in features like Insulin, BMI, etc.
   - Feature scaling using StandardScaler
2. *Train-Test Split*:
   - 80% Training, 20% Testing
3. *Model(s) Used*:
   - Logistic Regression (you can replace this with your algorithm)
   - Random Forest Classifier
   - (Optional) SVM, KNN for comparison

---

## 📊 Evaluation Metrics

- *Accuracy*
- *Precision*
- *Recall*
- *F1 Score*
- *Confusion Matrix*
- *ROC-AUC Curve*

---

## 📈 Results

| Model               |Train Accuracy|Test Accuracy|
|---------------------|--------------|-------------|
| Logistic Regression | %            | %           |
| Random Forest       | %            | %           |

(Values are just samples; update with your own results)

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/bv8904/diabetes-prediction.git
   cd diabetes-prediction
