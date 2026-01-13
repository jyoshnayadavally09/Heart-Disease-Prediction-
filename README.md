# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the **10-year risk of heart disease** using the **Framingham Heart Study dataset** and multiple **Machine Learning classification models**.  
It demonstrates a complete ML workflow including data preprocessing, model training, evaluation, and comparison.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help in timely medical intervention.  
This project uses patient health parameters to predict whether a person is at risk of developing heart disease within the next 10 years.

---

## 🧠 Machine Learning Models Used

The following classification models were implemented and compared:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Naive Bayes  

The best-performing model is selected based on **accuracy and evaluation metrics**.

---

## 📊 Dataset Information

**Dataset:** Framingham Heart Study (`framingham.csv`)

### Features Used:
- `age` – Age of the patient  
- `Sex_male` – Gender (1 = Male, 0 = Female)  
- `cigsPerDay` – Cigarettes smoked per day  
- `totChol` – Total cholesterol level  
- `sysBP` – Systolic blood pressure  
- `glucose` – Glucose level  

**Target Variable:**
- `TenYearCHD`  
  - `1` → At risk of heart disease  
  - `0` → Not at risk  

---

## ⚙️ Project Workflow

1. Data loading and cleaning  
2. Feature selection  
3. Feature scaling using StandardScaler  
4. Train-test split  
5. Model training  
6. Model evaluation  
7. Performance comparison  
8. Confusion matrix visualization  

---

## 📈 Evaluation Metrics

Each model is evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📂 Project Structure

