# 🩺 Diabetes Prediction Model

## 📌 Overview

This project predicts whether a patient is likely to have diabetes using machine learning. It uses the **Pima Indians Diabetes Dataset** and applies Logistic Regression for accurate and interpretable binary classification.

---

## 📊 Dataset

* Source: Kaggle
* Dataset: Pima Indians Diabetes Database
* Link: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

### 📁 Features:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

### 🎯 Target:

* `Outcome`

  * 0 → No Diabetes
  * 1 → Diabetes

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn

---

## 🔍 Project Workflow

1. Data Loading
2. Data Cleaning (handling missing/zero values)
3. Feature Selection
4. Data Splitting (Train/Test)
5. Feature Scaling (Standardization)
6. Model Training (Logistic Regression)
7. Model Evaluation

---

## 🤖 Model Used

* Logistic Regression

  * Chosen for simplicity and interpretability
  * Works well for binary classification problems

---

## 📈 Performance

* Accuracy: **~85%**
* Evaluation Metrics:

  * Confusion Matrix
  * Classification Report (Precision, Recall, F1-score)

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Project

```bash
python diabetes_model.py
```

---

## 📦 Requirements

* pandas
* numpy
* scikit-learn

---

## 💡 Example Prediction

The model takes patient health data as input and predicts:

* `0` → No Diabetes
* `1` → Diabetes

---

## 📌 Future Improvements

* Add more advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy using Streamlit or Flask
* Add visualization dashboard

---

## 👤 Author

**Abdul Ahad**

* GitHub: https://github.com/abdul9870

---
