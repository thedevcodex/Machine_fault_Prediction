# 🤖 Machine Fault Prediction

## 📌 Overview

This project uses Machine Learning to predict whether an industrial machine is in a **Normal** or **Fault** condition based on its operating and maintenance parameters.

The goal is to help identify potential machine faults early and support **preventive maintenance**.

## 🎯 Business Objective

* Detect potential machine faults early
* Reduce unexpected machine downtime
* Support preventive maintenance decisions
* Improve machine reliability and efficiency

## 📊 Dataset

The dataset contains **10,000 records and 13 features**, including:

* Temperature
* Vibration
* Pressure
* RPM
* Current
* Voltage
* Operating Hours
* Load Percentage
* Maintenance Count
* Last Maintenance Days
* Failure History

**Target:** `Machine_Status` — Normal / Fault

## 🔍 Project Workflow

```text
Data Understanding
       ↓
Data Cleaning
       ↓
EDA
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
Model Training
       ↓
Model Comparison
       ↓
Hyperparameter Tuning
       ↓
Final Model Selection
```

## 🤖 Models Used

* Logistic Regression
* Support Vector Classifier 

## 📏 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

## 🏆 Final Model

After comparing the models and performing hyperparameter tuning, **SVC (Support Vector Classifier)** was selected as the final model based on its overall evaluation performance.

## 🛠️ Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab 

##

Data Science & Machine Learning Enthusiast
