# 📊 **Placement Prediction Model Using Logistic Regression**

![GitHub Repo Sticker](https://img.shields.io/badge/GitHub-Repo-brightgreen?style=flat&logo=github) ![Python Version](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python) 

---

## 🧠 **Overview**

This repository showcases a simple **Machine Learning Model** for predicting whether a student will get placed based on their **CGPA and IQ** scores using **Logistic Regression**. It is built using **Python**, **pandas**, **scikit-learn**, and other libraries to provide insights into feature selection, preprocessing, model training, and evaluation.

---

## 🚀 **Key Features**

- **Data Exploration & Preprocessing**: 
  - Dataset cleaning and exploration using pandas.  
  - Scaled input features using `StandardScaler` for uniformity.
- **Model Implementation**:
  - Implemented **Logistic Regression** for binary classification.
  - Split data into train-test for evaluation using `train_test_split`.
- **Model Evaluation**:
  - Accuracy achieved: **0.9 (90%)**.
  - Decision boundary visualization with `mlxtend`.
- **Model Saving**:
  - Saved trained model using `pickle` for future deployment.

---

## 🛠️ **Tech Stack**

- **Python** 🐍
- **pandas** 📊
- **NumPy** 🖥️
- **scikit-learn** ⚙️
- **Matplotlib** 📊
- **mlxtend** 🔮
- **pickle** 📦
---

## 🖥️ **How It Works**

1. **Data Exploration**: The dataset contains student placement information based on CGPA and IQ scores.
2. **Preprocessing**:
   - Cleaned and scaled feature data.
   - Selected important features (`cgpa`, `iq`) for model training.
3. **Model Training**:
   - Applied **Logistic Regression** to classify students based on their likelihood of being placed.
4. **Model Testing & Evaluation**:
   - Accuracy checked on unseen data with **90% accuracy**.
5. **Visualization**:
   - Decision boundaries plotted to visualize model predictions.
6. **Deployment**:
   - Saved the trained model using **pickle** to integrate with other systems or use later.

---

## 📊 **Dataset**

Dataset used: `placement.csv`

The dataset consists of:
- **cgpa**: Student CGPA score.
- **iq**: IQ score of the student.
- **placement**: Binary value indicating if a student got placed (`1`) or not (`0`).

---

## 💾 **Getting Started**

To set up and run this locally:

### Clone the repository
```bash
git clone https://github.com/jaamyasir/Student-Placement-Test-model.git
