# Employee Attrition Prediction

This project focuses on predicting **employee attrition** — whether an employee is likely to leave the company — using machine learning techniques. The dataset is sourced from [Kaggle](https://www.kaggle.com), containing employee records with various demographic, workplace, and performance-related attributes.  

Attrition prediction helps organizations take proactive measures to improve employee retention, reduce turnover costs, and maintain a stable workforce.  

---

## 📂 Project Overview

- **Goal**: Build a predictive model to classify whether an employee will leave or stay.  
- **Dataset**: Kaggle’s Employee Attrition dataset (includes features like age, job role, work-life balance, satisfaction level, etc.).  
- **Approach**:  
  1. Data preprocessing and exploratory data analysis (EDA).  
  2. Feature engineering and selection.  
  3. Training classification models (e.g., Logistic Regression, Random Forest, Gradient Boosting).  
  4. Model evaluation using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.  
  5. Insights and recommendations based on key features influencing attrition.  

---

## 📊 Dataset

- **Source**: [Kaggle – Employee Attrition](https://www.kaggle.com/datasets)  
- **Target Variable**: `Attrition` (Yes/No)  
- **Features**:  
  - Demographics: Age, Gender, Education, Marital Status  
  - Job-related: Job Role, Department, Monthly Income, Years at Company, OverTime  
  - Performance: Job Satisfaction, Work-Life Balance, Environment Satisfaction  
  - Others: Distance from Home, Training Times Last Year, etc.  

---

## ⚙️ Technologies Used

- **Language**: Python 🐍  
- **Libraries**:  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`  
  - Notebook: `Jupyter`  

---

## 🚀 How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/employee-attrition-prediction.git
   cd employee-attrition-prediction

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Employee_Attrition_Prediction.ipynb


## 📈 Results

-Built multiple classification models and compared their performance.
-Identified key factors contributing to attrition (e.g., Overtime, Monthly Income, Job Satisfaction).
-Achieved strong predictive accuracy and insights for HR decision-making.

## 🔮 Future Work

-Test with deep learning models (e.g., Neural Networks).
-Deploy the model as a web app/dashboard.
-Explore SHAP/LIME for explainable AI insights.
