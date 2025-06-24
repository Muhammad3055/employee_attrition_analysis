# employee_attrition_analysis

# Predict Employee Attrition

This project helps predict whether an employee will leave a company or not using machine learning. We used the **IBM HR Analytics Dataset**, which contains 1,470 employee records with features like age, job role, income, overtime, satisfaction, etc.

## 🧠 Goal
- Predict employee attrition (leave/stay)
- Understand key reasons behind employee turnover
- Help HR take steps to retain employees

## 📊 Dataset
- From: IBM (available on Kaggle)
- Rows: 1,470 employees
- Features: Job role, income, age, distance from home, satisfaction, etc.
- Target: `Attrition` (Yes or No)

## 🔁 ML Pipeline

1. **Exploratory Data Analysis (EDA)**  
   - Checked attrition by job role, income, satisfaction, overtime, etc.
   - Found patterns (e.g., more attrition among people who work overtime)

2. **Preprocessing**
   - Encoded categories
   - Split data into training/testing sets
   - Balanced classes

3. **Models Used**
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Gradient Boosting

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

5. **Explainability**
   - **SHAP**: Showed most important features influencing decisions
   - **LIME**: Explained individual predictions

## ✅ Key Findings

- **Top reasons employees leave**:
  - Frequent overtime
  - Low job satisfaction
  - Long distance from home
  - Low salary

## 💡 HR Suggestions

- Reduce overtime
- Improve job satisfaction
- Provide flexible work options
- Review salary structure

## 📎 How to Run

1. Install libraries:
pip install pandas numpy matplotlib seaborn scikit-learn shap xgboost lime

2. Download the dataset from [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

3. Run the Jupyter notebook above 
