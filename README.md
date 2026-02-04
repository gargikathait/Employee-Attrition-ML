# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview
Employee attrition is a critical challenge for organizations as it impacts productivity, cost, and team morale.  
This project aims to predict whether an employee is likely to leave the organization using machine learning techniques.  
By analyzing employee demographic, job-related, and satisfaction data, the model helps HR teams take proactive retention measures.

---

## 📊 Dataset Details
- **Dataset Name:** IBM HR Analytics Employee Attrition Dataset  
- **Source:** Kaggle  
- **File Format:** CSV  
- **Target Variable:** Attrition (Yes / No → 1 / 0)

Dataset link:  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## 🔍 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Checked for missing values and duplicate records
- Analyzed attrition distribution
- Studied relationships between attrition and:
  - Department
  - Job Satisfaction
  - Monthly Income
- Visualizations were created using Matplotlib and Seaborn

---

## 🧹 Data Preprocessing
- Converted target variable (`Attrition`) into binary values
- Encoded categorical variables using Label Encoding
- Selected relevant features
- Split data into training and testing sets
- Applied feature scaling (for consistency)

---

## 🤖 Machine Learning Model
- **Model Used:** Random Forest Classifier  
- **Reason for Selection:**  
  - Handles non-linear relationships effectively  
  - Reduces overfitting by combining multiple decision trees  
  - Provides feature importance for better interpretability  

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

**Accuracy Achieved:** ~85-88% (may vary slightly depending on random state)

---

## 🔑 Key Observations
- Employees with low job satisfaction have higher attrition rates
- Monthly income and overtime significantly impact attrition
- Random Forest identifies important features contributing to employee turnover

---

## 🚀 Suggestions for Improvement
- Apply hyperparameter tuning (GridSearchCV)
- Handle class imbalance using SMOTE
- Try advanced models like XGBoost or Gradient Boosting

---

## ⚙️ Steps to Run the Project
1. Clone the repository
2. Open the project folder in VS Code
3. Open `employee_attrition.ipynb`
4. Run the following command in the notebook:
5. Restart the kernel
6. Run all notebook cells sequentially

---

## 🛠️ Technologies & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Repository Structure
Employee-Attrition-ML/
│
├── employee_attrition.ipynb
├── employee_attrition.csv
├── requirements.txt
└── README.md

---

## ✅ Conclusion
The Random Forest model effectively predicts employee attrition and highlights key factors influencing employee turnover.  
This project demonstrates the practical application of machine learning in HR analytics and decision-making.

# Employee-Attrition-ML
