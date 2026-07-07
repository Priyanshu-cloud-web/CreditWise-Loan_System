# 💳 CreditWise Loan System

A Machine Learning project for predicting loan approval based on an applicant's financial, demographic, and credit-related information. This project performs complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and prediction to assist financial institutions in making loan approval decisions.

---

## 📌 Project Overview

The CreditWise Loan System analyzes applicant data and predicts whether a loan application should be approved. It follows a complete Machine Learning workflow, including:

- Data Loading
- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Encoding
- Feature Scaling
- Model Training
- Model Evaluation
- Loan Approval Prediction

---


## 📊 Dataset Features

The dataset contains applicant information such as:

| Feature | Description |
|----------|-------------|
| Applicant_ID | Applicant Identifier |
| Applicant_Income | Monthly Income |
| Coapplicant_Income | Co-applicant Income |
| Employment_Status | Employment Type |
| Age | Applicant Age |
| Marital_Status | Married/Single |
| Dependents | Number of Dependents |
| Credit_Score | Credit Score |
| Existing_Loans | Existing Loans |
| DTI_Ratio | Debt-to-Income Ratio |
| Savings | Total Savings |
| Collateral_Value | Value of Collateral |
| Loan_Amount | Requested Loan Amount |
| Loan_Term | Loan Duration |
| Loan_Purpose | Purpose of Loan |
| Property_Area | Rural / Urban / Semiurban |
| Education_Level | Education |
| Gender | Applicant Gender |
| Employer_Category | Employer Type |
| Loan_Approved | Target Variable |

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Machine Learning Workflow

### 1. Data Collection

- Load dataset using Pandas.

### 2. Data Preprocessing

- Handle missing values
- Separate numerical and categorical features
- Impute missing values
- Remove inconsistencies

### 3. Exploratory Data Analysis (EDA)

Visualizations include:

- Loan Approval Distribution
- Credit Score Distribution
- Income Distribution
- Correlation Heatmap
- Feature Relationships

---

### 4. Feature Engineering

- Encode categorical variables
- Scale numerical features
- Prepare dataset for training

---

### 5. Model Training

The project can be trained using models such as:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors

---

### 6. Model Evaluation

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Priyanshu-cloud-web/CreditWise-Loan_System.git
```

Move into the project directory

```bash
cd CreditWise-Loan_System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Or install them directly

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## 📊 Output

The system predicts whether a loan application is:

- ✅ Approved
- ❌ Rejected

based on the applicant's financial and personal details.


## 👨‍💻 Author

**Priyanshu**

GitHub: https://github.com/Priyanshu-cloud-web
