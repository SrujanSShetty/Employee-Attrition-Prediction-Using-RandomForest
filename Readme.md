# Employee Attrition Prediction Using Random Forest

This project uses machine learning to predict whether an employee is likely to leave an organization, helping HR teams take proactive steps toward retention. The dataset is sourced from IBM's HR Analytics data and focuses on employee demographics, work behavior, compensation, and satisfaction levels.

---

## 📊 Problem Statement

**Objective**: Predict employee attrition (`Yes` or `No`) using classification models based on features like income, age, job role, distance from home, overtime, etc.

**Use Case**: 
- Reduce turnover by identifying at-risk employees
- Inform HR policies around salary, work-life balance, and engagement

---

## 🧠 Tools & Technologies Used

- **Python 3.10+**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for machine learning
- **Random Forest Classifier** for modeling
- **Jupyter Notebook**

---

## 📁 Dataset

- 📂 File: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- 📌 Source: IBM Watson Analytics (public domain)
- 📈 35 features including Age, MonthlyIncome, DistanceFromHome, OverTime, YearsAtCompany, etc.
- 🎯 Target variable: `Attrition` (Yes = left, No = stayed)

---

## 🔁 Workflow

1. **Data Cleaning**  
   Dropped irrelevant or constant features like `EmployeeNumber`, `StandardHours`, etc.

2. **Feature Engineering**  
   - Encoded target variable as binary (Yes = 1, No = 0)
   - One-hot encoded categorical features

3. **Modeling**  
   - Train-test split (80/20)
   - Random Forest Classifier for predictive modeling
   - Evaluated with confusion matrix, precision, recall, F1-score

4. **Feature Selection**  
   - Feature importance from Random Forest
   - Visualized top 10 influential features

---

## 📈 Model Performance

| Metric       | Score (Example) |
|--------------|------------------|
| Accuracy     | ~84%             |
| Precision    | 73%              |
| Recall       | 60%              |
| F1-Score     | 66%              |

> These may vary slightly depending on train-test split and parameters.

---

## 🔍 Key Insights

- **Monthly Income**, **OverTime**, and **Total Working Years** are top predictors of attrition.
- Employees who are **younger**, have **low pay**, or **long commutes** are more likely to leave.
- The model helps HR focus efforts on specific high-risk profiles.

---

## 📌 Future Work

- Add SHAP values for explainability
- Try advanced models (XGBoost, LightGBM)
- Deploy via Flask or Streamlit for HR dashboarding

---

## 👨‍💻 Author

**Srujan Shekar Shetty**  
Master's in Information Technology and Management, Illinois Tech  
GitHub: [your GitHub profile]  
LinkedIn: [your LinkedIn profile]

---

## 🏷️ Tags

`Machine Learning` `HR Analytics` `Employee Attrition` `Random Forest` `Classification` `Python` `Scikit-learn`