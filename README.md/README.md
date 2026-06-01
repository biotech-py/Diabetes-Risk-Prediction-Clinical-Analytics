# 🩺 Diabetes Risk Prediction & Clinical Analytics

## 📌 Project Overview

This project combines Healthcare Analytics, Machine Learning, and Power BI to predict diabetes risk and identify key clinical risk factors using the Pima Indians Diabetes Dataset.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Logistic Regression Modeling
- Model Evaluation
- Power BI Dashboard Development

---

## 🎯 Objective

To develop a predictive model capable of identifying diabetes risk and uncover clinically relevant factors associated with Type-2 Diabetes.

---

## 📊 Dataset Information

**Dataset:** Pima Indians Diabetes Dataset

### Dataset Summary

| Feature | Description |
|----------|------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Family history risk score |
| Age | Age of patient |
| Outcome | Diabetes status (0 = No, 1 = Yes) |

**Total Records:** 768

---

## 🧹 Data Cleaning

The following columns contained medically impossible zero values:

- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI

### Cleaning Strategy

- Replaced invalid zeros with missing values
- Imputed missing values using median values
- Verified data integrity before modeling

---

## 📈 Exploratory Data Analysis

### Key Insights

- Approximately 35% of patients were diabetic.
- Glucose showed the strongest relationship with diabetes.
- Obesity was highly prevalent among diabetic patients.
- Older patients demonstrated higher diabetes prevalence.

---

## 🤖 Machine Learning Model

### Model Used

**Logistic Regression**

### Performance Metrics

| Metric | Score |
|----------|----------|
| Accuracy | 75.97% |
| ROC-AUC | 0.819 |
| Cross Validation Score | 75.90% |

---

## 🔍 Top Clinical Risk Factors

The model identified the following major predictors of diabetes:

1. Glucose
2. Obese Status
3. Age
4. Overweight Status
5. BMI

These findings align with established clinical understanding of Type-2 Diabetes risk factors.

---

# 📊 Power BI Dashboard

## Clinical Overview

![Clinical Overview](IMAGES/clinical_overview.png)

---

## Risk Factors Analysis

![Risk Factors](IMAGES/risk_factors.png)

---

## Model Performance

![Model Performance](IMAGES/model_performance.png)

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Power BI
- GitHub

---

## 📂 Project Structure

```text
Diabetes-Risk-Prediction-Clinical-Analytics
│
├── DASHBOARD
├── DATA
├── IMAGES
├── NOTEBOOKS
├── OUTPUTS
├── requirements.txt
└── README.md
```

---

## 🚀 Project Highlights

- End-to-End Healthcare Analytics Project
- Machine Learning Based Diabetes Prediction
- Feature Engineering Using BMI Categories
- Logistic Regression Classification Model
- ROC-AUC Evaluation
- Clinical Risk Factor Identification
- Interactive Power BI Dashboard

---

## 👨‍💻 Author

**Nirupam Joarder**

Biotechnology Graduate | Data Analytics | Healthcare Analytics
