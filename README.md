# 🤖 Thiranex Task 2 – Predictive Modeling Using Machine Learning

## 📌 Project Overview

This project was developed as part of the **Thiranex Machine Learning Internship – Task 2: Predictive Modeling Using Machine Learning**.

The project uses supervised machine learning techniques to predict whether a student is likely to **Pass or Fail** based on academic and attendance-related features.

Two machine learning algorithms were implemented and evaluated:

- 🌳 Random Forest Classifier
- 🌿 Decision Tree Classifier

The models were trained and tested using the **UCI Student Performance Dataset**.

## 🎯 Objective

The main objective of this project is to build a predictive machine learning model that can:

- Analyze student-related data
- Train supervised machine learning models
- Predict student outcomes
- Evaluate model performance
- Visualize classification performance
- Compare different machine learning algorithms

## 📊 Dataset

The project uses the **Student Performance Dataset** from the UCI Machine Learning Repository.

The dataset contains information related to:

- Age
- Study time
- Previous failures
- Absences
- First period grade (G1)
- Second period grade (G2)
- Final grade (G3)

The final grade (G3) was used to create the target variable.

### Target Variable

**Pass = 1** → Student Passes  
**Pass = 0** → Student Fails

A student is considered to have passed when:

**G3 >= 10**

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

## 🤖 Machine Learning Models

### 1. Random Forest Classifier

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction performance.

### 2. Decision Tree Classifier

Decision Tree is a supervised learning algorithm that makes predictions using a tree-like structure of decision rules.

## 🔄 Machine Learning Workflow

Dataset → Data Loading → Data Exploration → Feature Selection → Target Variable Creation → Train-Test Split → Model Training → Prediction → Model Evaluation → Confusion Matrix → ROC Curve → Feature Importance → New Student Prediction

## 📈 Features Used

The following features were used to train the models:

- Age
- Study Time
- Previous Failures
- Absences
- G1 Grade
- G2 Grade

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

A model comparison was also performed to understand the difference in predictive performance.

## 📉 Visualizations

The project includes:

### Confusion Matrix

Shows the number of correct and incorrect Pass/Fail predictions.

### ROC Curve

Shows the classification performance of the Random Forest model at different classification thresholds.

### Feature Importance

Shows the relative contribution of different input features to the Random Forest model.

### Model Comparison

Compares the accuracy of the Random Forest and Decision Tree models.

## 🎓 New Student Prediction

The trained Random Forest model can predict the outcome of a new student based on:

- Age
- Study time
- Previous failures
- Absences
- G1 grade
- G2 grade

The model outputs:

**PASS** or **FAIL**

along with the predicted probabilities.

## 💻 Project Notebook

The complete implementation is available in:

**Thiranex_Task2_Predictive_Modeling.ipynb**

The notebook contains the complete machine learning workflow, code, model evaluation and visualizations.

## 🚀 Key Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature selection
- Supervised machine learning
- Classification algorithms
- Random Forest
- Decision Trees
- Train-test splitting
- Model evaluation
- Confusion matrices
- ROC curves
- AUC evaluation
- Feature importance
- Making predictions using trained models

## 📌 Internship Details

**Organization:** Thiranex  
**Task:** Task 2 – Predictive Modeling Using Machine Learning  
**Domain:** Machine Learning

## 👩‍💻 Author

**Divya Banuka**

B.Tech – Artificial Intelligence & Machine Learning

## ⭐ Project Status

✅ Completed
