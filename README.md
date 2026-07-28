# Employee-Attrition-Prediction

# 👨‍💼 Employee Attrition Prediction using Machine Learning

# 📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations worldwide. Losing experienced employees not only increases recruitment costs but also affects productivity, employee morale, customer satisfaction, and overall business performance.

This project uses **Machine Learning** to predict whether an employee is likely to leave the organization based on demographic, professional, and workplace-related factors.

The project follows a complete Data Science workflow including:

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Machine Learning Model Building
- Model Evaluation
- Prediction
- Business Insights

# 🎯 Problem Statement

Employee turnover causes significant financial losses to organizations.

Hiring a new employee involves:

- Recruitment Cost
- Training Cost
- Productivity Loss
- Knowledge Transfer Issues
- Increased Workload on Existing Employees

Instead of reacting after an employee resigns, organizations can use predictive analytics to identify employees who may leave in the future.

This project solves this problem using supervised machine learning.

---

# 🚀 Objectives

The primary objectives of this project are:

- Predict employee attrition accurately.
- Analyze factors affecting employee resignation.
- Build a reliable Machine Learning model.
- Compare different classification algorithms.
- Improve HR decision-making.
- Reduce employee turnover.
- Increase employee retention.
- Support data-driven workforce planning.

---

# 📂 Dataset Information

Dataset Used:

**IBM HR Analytics Employee Attrition & Performance Dataset**

The dataset contains employee information including:

- Age
- Gender
- Department
- Education
- Monthly Income
- Job Role
- Job Level
- Business Travel
- Overtime
- Work-Life Balance
- Environment Satisfaction
- Job Satisfaction
- Years at Company
- Years Since Last Promotion
- Years with Current Manager
- Distance from Home
- Training Times Last Year
- Performance Rating
- Stock Option Level
- Marital Status
- Total Working Years

Target Variable:

```
Attrition

Yes → Employee Left

No → Employee Stayed
```

The IBM HR Analytics dataset is widely used for HR analytics and employee retention research. :contentReference[oaicite:0]{index=0}

---

# 📊 Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Encoding Categorical Features
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
Machine Learning Models
      │
      ▼
Performance Evaluation
      │
      ▼
Prediction
```

---

# 🛠 Technologies Used

Programming Language

- Python

Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib

Development Environment

- Jupyter Notebook
- VS Code

Version Control

- Git
- GitHub

---

# 📈 Exploratory Data Analysis

EDA includes:

- Missing Value Analysis
- Duplicate Record Detection
- Data Cleaning
- Statistical Summary
- Correlation Analysis
- Distribution Plots
- Count Plots
- Heatmaps
- Boxplots
- Histograms
- Pairplots

Important insights were extracted regarding:

- Overtime
- Monthly Income
- Job Satisfaction
- Environment Satisfaction
- Business Travel
- Work-Life Balance
- Years at Company

These features showed strong relationships with employee attrition.

---

# ⚙ Data Preprocessing

The preprocessing pipeline includes:

✔ Handling Missing Values

✔ Removing Duplicates

✔ Feature Encoding

- One-Hot Encoding
- Label Encoding

✔ Feature Scaling

- StandardScaler

✔ Train-Test Split

✔ Pipeline Creation

✔ Column Transformer

---

# 🤖 Machine Learning Models

Different classification algorithms can be evaluated, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Gradient Boosting

The selected model is trained using the processed dataset and evaluated using multiple classification metrics. Logistic Regression is a common strong baseline for this IBM HR dataset. :contentReference[oaicite:1]{index=1}

---

# 📊 Model Evaluation Metrics

The model performance can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

These metrics help determine how effectively the model predicts employee attrition.

---

# 📌 Features Used

Some important features include:

- Age
- Monthly Income
- Job Role
- Job Level
- Education
- Overtime
- Business Travel
- Environment Satisfaction
- Job Satisfaction
- Work-Life Balance
- Marital Status
- Distance From Home
- Years at Company
- Years Since Last Promotion
- Years With Current Manager
- Total Working Years
- Stock Option Level
- Training Times Last Year

# 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
jupyter
```

# 🔮 Future Improvements

Future enhancements may include:

- Streamlit Web Application
- Flask API
- Power BI Dashboard
- XGBoost Model
- LightGBM Model
- CatBoost Model
- Hyperparameter Tuning
- Cross Validation
- SHAP Explainability
- Feature Importance Dashboard
- Real-time Prediction System
- Cloud Deployment (AWS / Azure)

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Machine Learning
- Classification Algorithms
- Model Evaluation
- Pipeline Creation
- HR Analytics
- Predictive Analytics
- Git & GitHub


