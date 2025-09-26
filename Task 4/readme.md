# 📌 Customer Churn Prediction using Machine Learning

## 📖 Introduction

Customer churn prediction is a key application of machine learning in business analytics. Churn occurs when customers stop doing business with a company, and being able to predict churn allows businesses to take proactive steps to retain customers.
This project focuses on building a churn prediction model using **Logistic Regression** and **XGBoost**, comparing their performance, and selecting the better-performing model. The dataset undergoes preprocessing, exploratory analysis, encoding, balancing, and model optimization with **GridSearchCV**.

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
3. **Distribution Analysis:** Visualized churn distribution, and service usage with **Matplotlib** and **Seaborn**.
4. **Correlation Analysis:** Explored relationships between features and target variable.
5. **Class Imbalance Check:** Apply SMOTE technique to balance the target variable.

---

## ⚙️ Data Preprocessing

1. **Handling Missing Values** – Removed or imputed missing data where applicable.
2. **Encoding Categorical Features** – Applied **One-Hot Encoding** to convert categorical (text) columns into numerical format.
3. **Balancing the Dataset** – Used **SMOTE (Synthetic Minority Oversampling Technique)** to handle class imbalance.
4. **Train-Test Split** – Split the dataset into training and testing sets for model evaluation.

---

## 🤖 Model Training & Evaluation

Two machine learning algorithms were trained and optimized using **GridSearchCV**:

* **Logistic Regression**

  * A simple linear model used as a baseline for classification.
  * Achieved good performance but slightly less than XGBoost.

* **XGBoost (Extreme Gradient Boosting)**

  * An advanced boosting algorithm.
  * Outperformed Logistic Regression with higher accuracy and better handling of complex patterns.
  * Selected as the final model.

---

## 📊 Results

* Both Logistic Regression and XGBoost performed well after hyperparameter tuning.
* **XGBoost showed a slight edge over Logistic Regression**, making it the final choice for churn prediction.

---

## 🧠 Technologies & Libraries Used
* **Python**
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Preprocessing, Logistic Regression, GridSearchCV, SMOTE
* **Imbalanced-learn** – SMOTE for balancing the dataset
* **XGBoost** – Advanced machine learning model for classification
* **LogisticRegression** – machine learning algorithm for classification




