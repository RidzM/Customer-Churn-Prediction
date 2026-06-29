# Customer Churn Prediction Using Machine Learning

## Project Overview
Predicts whether a customer will leave (churn) a company based on historical behaviour data using multiple Machine Learning algorithms.

**Domain:** Artificial Intelligence 

---

## Folder Structure
```
Customer-Churn-Prediction/
├── dataset/
│   └── customer_churn.csv          ← 1000-record dataset (11 features)
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb  ← Full Jupyter Notebook (main file)
├── src/
│   └── project.py                  ← Standalone Python script
├── report/
│   ├── churn_distribution.png
│   ├── categorical_vs_churn.png
│   ├── numerical_distributions.png
│   ├── correlation_heatmap.png
│   ├── boxplots_vs_churn.png
│   ├── confusion_matrices.png
│   ├── roc_curves.png
│   ├── model_comparison.png
│   ├── feature_importance.png
│   ├── risk_distribution.png
│   └── probability_distribution.png
└── README.md
```

---

## Dataset Features
| Feature | Description |
|---|---|
| CustomerID | Unique identifier |
| Gender | Male / Female |
| Age | Customer age |
| Tenure | Months with company |
| MonthlyCharges | Monthly billing amount |
| TotalCharges | Total amount billed |
| ContractType | Month-to-month / One year / Two year |
| PaymentMethod | Electronic check / Mailed check / Bank transfer / Credit card |
| InternetService | DSL / Fiber optic / No |
| CustomerSupportCalls | Number of support calls made |
| **Churn** | **Target: Yes / No** |

---

## Technologies Used
- **Language:** Python 3.x
- **Notebook:** Jupyter Notebook / Google Colab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

---

## ML Algorithms
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost

---

## How to Run

### Option 1: Jupyter Notebook (Recommended)
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost notebook
jupyter notebook notebooks/Customer_Churn_Prediction.ipynb
```

### Option 2: Python Script
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
python src/project.py
```

---

## Project Workflow
1. Data Collection & Loading
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training (with 5-Fold Cross Validation)
6. Model Evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)
7. Prediction & Risk Classification
8. Business Insights & Conclusions

---

## Learning Outcomes
Customer Analytics
Data Preprocessing
Classification Algorithms
Model Evaluation Metrics
Feature Engineering
Business Decision Support

---

## 👤 Author
Student Project — AI/ML Course
