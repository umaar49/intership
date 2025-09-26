# 📌 Customer Churn Prediction using Machine Learning

## 📖 Introduction

Customer churn prediction is a key application of machine learning in business analytics. Churn occurs when customers stop doing business with a company, and being able to predict churn allows businesses to take proactive steps to retain customers.
This project focuses on building a churn prediction model using **Logistic Regression**  and evaluate the model on test dataset using confusion atrix.

---

## 📂 Dataset

* **Dataset Description:**
  The dataset contains customer-level information such as SeniorCitizen,	Partner,	Dependents,	tenure,	PhoneService,	MultipleLines, and whether the customer churned or not.
* **Target Variable:** `Churn` (Yes/No)

---

## 🔎 Exploratory Data Analysis (EDA)

The following steps were performed during EDA:

1. **Data Inspection:** Checked dataset shape, missing values, duplicates, and overall data quality.
2. **Statistical Summary:** Used descriptive statistics (`.describe()`) to understand numerical features.
3. **Distribution Analysis:** Visualized churn distribution, customer demographics, and service usage with **Matplotlib** and **Seaborn**.
4. **Correlation Analysis:** Explored relationships between features and target variable.
5. **Class Imbalance Check:** Found churned customers to be fewer than non-churned customers, requiring balancing techniques.

---

## ⚙️ Data Preprocessing

1. **Handling Missing Values** – Removed or imputed missing data where applicable.
2. **Encoding Categorical Features** – Applied **One-Hot Encoding** to convert categorical (text) columns into numerical format.
3. **Balancing the Dataset** – Used **SMOTE (Synthetic Minority Oversampling Technique)** to handle class imbalance.
4. **Train-Test Split** – Split the dataset into training and testing sets for model evaluation.

---

## 🤖 Model Training & Evaluation

* **Logistic Regression**

  * A simple linear model used as a baseline for classification.
  * Achieved good performance on test dataset.

---

## 📊 Results

* Logistic Regression performed well with accuracy of 82% on test datatset.

---

## 🧠 Technologies & Libraries Used

* **Python**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Preprocessing, Logistic Regression, GridSearchCV, SMOTE
* **Imbalanced-learn** – SMOTE for balancing the dataset
* **LogisticRegression** –  machine learning model for classification




