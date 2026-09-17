# 🩺 Diabetes Prediction

A machine learning project to predict diabetes based on patient health and medical-related features.

## 📌 Project Overview

Diabetes is a chronic health condition that can affect an individual's overall health and quality of life. Data analysis and machine learning can be used to identify patterns in health-related data and build predictive models.

This project focuses on developing a machine learning classification model to predict whether a patient is likely to have diabetes based on several health-related features.

The project was developed using **Python** in **Google Colab**.

## 🎯 Objectives

* Understand and explore the diabetes dataset.
* Perform exploratory data analysis (EDA).
* Prepare and preprocess the data for machine learning.
* Build a classification model to predict diabetes.
* Evaluate the model using classification metrics.
* Identify patterns and relationships between patient features and diabetes outcomes.

## 📊 Dataset

The dataset contains information about patients and several health-related characteristics.

### Features

| Feature                    | Description                  |
| -------------------------- | ---------------------------- |
| `Pregnancies`              | Number of pregnancies        |
| `Glucose`                  | Plasma glucose concentration |
| `BloodPressure`            | Diastolic blood pressure     |
| `SkinThickness`            | Triceps skin fold thickness  |
| `Insulin`                  | 2-Hour serum insulin         |
| `BMI`                      | Body Mass Index              |
| `DiabetesPedigreeFunction` | Diabetes pedigree function   |
| `Age`                      | Patient age                  |
| `Outcome`                  | Diabetes outcome             |

The `Outcome` variable is the target variable:

* `0` → No diabetes indication
* `1` → Diabetes indication

## 🔎 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the structure and characteristics of the dataset.

The analysis includes:

* Checking the dataset dimensions and data types
* Examining descriptive statistics
* Checking the distribution of the target variable
* Analyzing feature distributions
* Exploring relationships between features
* Identifying potential data quality issues

## 🧹 Data Preprocessing

The data preprocessing stage includes preparing the dataset before applying machine learning.

The workflow includes:

1. Loading the dataset
2. Checking the data structure
3. Checking missing or invalid values
4. Separating features and target
5. Preparing the data for modeling
6. Splitting the dataset into training and testing sets
7. Applying feature transformation when required

## 🤖 Machine Learning

This project uses a **supervised machine learning classification approach**.

The workflow can be summarized as:

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Classification Model
   ↓
Prediction
   ↓
Model Evaluation
```

## 📈 Model Evaluation

The model performance is evaluated using several classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help evaluate how well the model distinguishes between patients with and without a diabetes indication.

> The final performance values are based on the results obtained from the notebook.

## 💡 Key Insights

The project demonstrates how patient health-related data can be analyzed and used as input for a machine learning classification model.

Through this project, I practiced:

* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature analysis
* Classification modeling
* Model evaluation
* Python-based data analysis

## 🛠️ Tools & Technologies

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

## 📁 Repository Structure

```text
diabetes-prediction/
│
├── Diabetes_Prediction.ipynb
└── README.md
```

## 🚀 Future Improvements

Possible improvements for this project include:

* Comparing multiple classification algorithms
* Hyperparameter tuning
* Cross-validation
* Feature selection
* Model interpretability
* Deploying the model as a simple prediction application

## 👩‍💻 Author

**Agustina Sri Astuti, S.Kom., M.Kom.**

IT Business Analyst | Business Process & System Analysis

📍 Bandar Lampung, Indonesia

---

⭐ This project is part of my portfolio to demonstrate practical skills in **Python, Data Analysis, and Machine Learning**.
