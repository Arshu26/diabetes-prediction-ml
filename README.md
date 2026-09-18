# 🩺 Diabetes Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting diabetes using machine learning techniques. The notebook covers the complete workflow from **data cleaning and exploratory data analysis (EDA)** to **data preprocessing, class-imbalance handling, model training, hyperparameter tuning, and evaluation**.

The project uses a **Random Forest Classifier** and applies **SMOTE and RandomUnderSampler** to address class imbalance.

> ⚠️ **Disclaimer:** This project is created for educational and machine-learning practice purposes. It is **not a medical diagnostic system** and should not be used for healthcare decisions.

---

## 🎯 Objectives

* Understand the diabetes prediction dataset
* Perform data cleaning and preprocessing
* Explore the dataset using EDA
* Analyze relationships between important features
* Handle categorical variables
* Handle class imbalance
* Train a Random Forest classification model
* Perform hyperparameter tuning using GridSearchCV
* Evaluate model performance
* Identify important features affecting predictions

---

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Imbalanced-learn**
* **Jupyter Notebook**

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Categorical Encoding
   ↓
Correlation Analysis
   ↓
Handle Class Imbalance
   ↓
Feature Scaling
   ↓
Random Forest Model
   ↓
Hyperparameter Tuning
   ↓
Model Evaluation
   ↓
Feature Importance
```

---

## 📊 Analysis Performed

The project includes:

* Dataset inspection
* Duplicate-value checking
* Missing-value analysis
* Distinct-value analysis
* Gender-category analysis
* Smoking-history analysis
* Distribution visualizations
* Correlation analysis
* Class-distribution analysis
* Feature preprocessing
* Feature importance analysis

---

## 🤖 Machine Learning Model

### Random Forest Classifier

A **Random Forest Classifier** is used for diabetes classification.

The project also performs **hyperparameter tuning using GridSearchCV** to identify suitable model parameters.

### Class Imbalance Handling

The target classes are imbalanced, so the project explores:

* **SMOTE (Synthetic Minority Over-sampling Technique)**
* **RandomUnderSampler**

This helps provide a more balanced training dataset.

---

## 📈 Model Evaluation

The trained model is evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix
* Feature Importance

Accuracy is considered together with the classification report and confusion matrix rather than being used as the only evaluation metric.

---

## 📁 Project Structure

```text
diabetes-prediction-ml/
│
├── Diabetes_Prediction_ML.ipynb
├── diabetes_prediction_dataset.csv
├── README.md
├── requirements.txt
└── .gitignore
```

> The dataset file should only be uploaded if its license/terms allow redistribution.

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/diabetes-prediction-ml.git
```

### 2. Open the project folder

```bash
cd diabetes-prediction-ml
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Diabetes_Prediction_ML.ipynb
```

Run the notebook cells sequentially.

---

## 📚 Skills Demonstrated

This project demonstrates practical experience with:

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Feature Engineering
* Categorical Encoding
* Feature Scaling
* Class Imbalance
* SMOTE
* Machine Learning
* Random Forest
* Hyperparameter Tuning
* Model Evaluation
* Feature Importance
* Python Data Science Libraries

---

## 👨‍💻 Author

**Mohd Arsalan**

BCA — Data Science & Artificial Intelligence

---

## ⭐ Project Purpose

This project was developed as part of my learning journey in **Data Science and Artificial Intelligence**, with a focus on applying machine-learning concepts to a real-world classification problem.
