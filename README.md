# ❤️ Heart Disease Prediction using Bagging Classifier

## 🧠 Project Overview

This project demonstrates the use of **Bagging Classifier (Ensemble Learning)** to predict whether a patient has heart disease based on medical attributes.

It focuses on improving model performance and reducing overfitting by combining multiple decision tree models.

---

## 📊 Dataset

The dataset contains medical attributes such as:

* Age
* Sex
* Cholesterol level
* Resting blood pressure
* Chest pain type
* Maximum heart rate
* And other clinical features

**Target Variable:**

* `0` → No Heart Disease
* `1` → Heart Disease

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

Performed analysis to understand the data:

* Checked for missing values
* Analyzed feature distributions
* Visualized correlations using heatmap
* Studied target variable distribution

---

## 🤖 Model Building

**Algorithm Used:**

* Bagging Classifier

**Base Model:**

* Decision Tree Classifier

**Concept:**
Bagging (Bootstrap Aggregation) builds multiple models using different subsets of data and combines their predictions to improve stability and accuracy.

---

## ⚙️ Model Training

* Train-Test Split applied
* Multiple estimators used to strengthen predictions

---

## 📈 Model Evaluation

Model performance evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix
* Classification Report

---

## 📊 Results

The Bagging Classifier improves prediction performance by reducing variance and providing more stable results compared to a single model.

---

## 📁 Project Structure

```
ML_Bagging/
│── bagging-classifier.ipynb
│── heart.csv
│── README.md
```

---

## 💡 Key Learnings

* Understanding Ensemble Learning (Bagging)
* Reducing overfitting using multiple models
* Importance of evaluation metrics
* Data visualization for insights

---

## 🔗 Future Improvements

* Hyperparameter tuning
* Compare with other models (Random Forest, XGBoost)
* Model deployment using Flask
* Cross-validation for better generalization.