# 🏥 Healthcare Analytics Project

## Predicting 30-Day Hospital Readmissions for Diabetes Patients

### 📌 Project Overview

This project focuses on predicting early hospital readmissions (<30 days) among diabetes patients using machine learning. The goal is to help hospitals identify high-risk patients at discharge and enable preventive interventions to reduce costs and improve care quality.

Dataset includes 10 years of clinical data from 130 U.S. hospitals with 101,766 patient records and 47+ features.

---

### 🎯 Business Objective

Hospital readmissions increase treatment costs and indicate gaps in care quality.
This project aims to:

* Identify high-risk patients before discharge
* Support clinical decision-making
* Reduce readmission-related healthcare costs
* Improve patient outcomes

---

### 📊 Dataset Information

* Source: UCI Machine Learning Repository
* Records: 101,766 patient encounters
* Features: Demographics, diagnoses, medications, lab tests, hospital visits
* Target variable: Early readmission (<30 days)

---

### ⚙️ Project Workflow

#### 1. Data Cleaning

* Removed columns with excessive missing values
* Handled categorical missing values using "Unknown" category
* Dropped non-informative ID columns

#### 2. Feature Engineering

Created new healthcare severity indicators:

* Total hospital visits
* Medication intensity
* Lab procedure intensity
* Procedure intensity

#### 3. Exploratory Data Analysis

Key findings:

* Higher readmission among elderly patients
* Longer hospital stays linked to increased risk
* Insulin dosage changes indicate unstable condition
* Prior hospital visits strongly predict readmission

#### 4. Modeling

Models used:

* Logistic Regression (baseline)
* Class-weighted Logistic Regression
* Random Forest
* SMOTE oversampling for class imbalance

#### 5. Model Evaluation

Metrics used:

* Recall (priority for healthcare risk detection)
* Precision
* F1-score
* Confusion matrix

---

### 📈 Key Insights

* Age groups 50+ showed higher readmission risk
* Insulin treatment changes were major predictors
* Patients with frequent prior hospital visits had significantly higher risk
* Longer hospital stays indicated severe conditions and higher readmission probability

---

### 🤖 Feature Importance

Top predictors identified:

* Age group
* Insulin treatment pattern
* Medication intensity
* Lab procedures
* Time in hospital
* Number of diagnoses

---

### 🧠 Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Matplotlib, Seaborn

---

### 💼 Business Impact

This project demonstrates how predictive analytics can:

* Assist hospitals in risk stratification
* Improve discharge planning
* Enable targeted patient monitoring
* Reduce operational and treatment costs

---

### 🚀 Future Improvements

* XGBoost and advanced tuning
* Deployment as clinical decision support tool
* Integration with hospital EHR systems
* Real-time prediction pipeline

---

### 📎 Dataset Source

UCI ML Repository – Diabetes 130-US Hospitals Dataset
https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008

---

### 👤 Author

Anshu Kumar
Data Analytics | Machine Learning | Healthcare Analytics
