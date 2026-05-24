# Loan Default Risk Analysis

Machine learning and business analytics project focused on predicting loan default risk using financial, demographic, and credit-related applicant data.

---

# Project Overview

Loan defaults pose significant financial risks for lending institutions by increasing credit losses and reducing portfolio profitability. This project applies data analytics and machine learning techniques to analyze applicant risk factors and develop predictive models capable of identifying high-risk loan applicants.

The project combines:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Classification modeling
- Regression analysis
- Business-focused recommendations

to support data-driven credit risk assessment and loan approval decisions.

---

# Business Problem

Financial institutions face major challenges in balancing:

- Customer acquisition
- Risk management
- Loan profitability
- Credit portfolio stability

Approving high-risk applicants can lead to increased defaults, while overly restrictive lending reduces revenue opportunities.

This project aims to improve loan approval decision-making by identifying key predictors of default risk and building predictive models for applicant classification.

---

# Objectives

The project aims to:

- Identify factors strongly associated with loan defaults
- Analyze applicant financial behavior and credit indicators
- Build predictive models for default classification
- Evaluate feature importance for risk assessment
- Generate business recommendations for loan approval optimization

---

# Tech Stack

## Programming & Analytics
- Python
- Pandas
- NumPy

## Visualization
- Matplotlib
- Seaborn

## Machine Learning
- Scikit-learn
- Random Forest Classifier
- Gradient Boosting
- Linear Regression
- XGBoost

## Development Environment
- Jupyter Notebook

---

# Repository Structure

```text
loan-default-risk-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── loan_default_analysis.ipynb
│
└── README.md
```

---

# Dataset Overview

The dataset contains approximately 2200 loan application records with financial, demographic, and credit-related features.

## Key Features

### Financial Information
- Monthly Income
- Debt-to-Income Ratio
- Revolving Credit Balance
- Amount Requested
- Amount Funded

### Credit Information
- FICO Range
- Credit Line Information
- Loan Interest Rate
- Previous Credit Inquiries

### Applicant Information
- Employment Length
- Home Ownership
- State
- Loan Purpose

### Target Variable
- Loan Default Status

---

# Methodology

## 1. Data Cleaning & Preprocessing

Performed:

- Missing value imputation
- Data type conversion
- Feature normalization
- Percentage formatting cleanup
- Numeric feature extraction
- Categorical encoding

Several features required transformation from string-based formats into usable numerical representations.

Examples include:
- Interest Rate
- Debt-to-Income Ratio
- FICO Range
- Employment Length

---

## 2. Feature Engineering

New analytical variables were created, including:

- Amount Difference
- Funding Ratio
- Monthly Debt Ratio
- Credit Line Ratio

These engineered features improved model interpretability and predictive capability.

---

## 3. Exploratory Data Analysis (EDA)

Exploratory analysis focused on:

- Loan default distribution
- Correlation analysis
- Income and interest rate relationships
- Home ownership trends
- Credit behavior patterns

Visualizations included:

- Histograms
- Correlation heatmaps
- Scatter plots
- Pie charts
- Feature importance plots

---

## 4. Classification Modeling

A Random Forest Classifier was used to predict whether applicants would default on loans.

### Classification Goals

- Identify high-risk applicants
- Improve loan approval decision-making
- Reduce portfolio default exposure

### Classification Performance

| Metric | Score |
|------|------|
| Accuracy | 99% |
| Default Recall | 88% |
| Weighted F1-Score | 99% |

The model demonstrated strong classification capability for identifying loan default risk.

---

## 5. Regression Analysis

Linear Regression was applied to analyze funding-related relationships and estimate loan funding differences.

The regression workflow supported additional quantitative insights into loan allocation patterns.

---

# Key Insights

The analysis revealed:

- Debt-to-income ratio is one of the strongest indicators of loan default risk.
- Lower FICO scores correlate strongly with higher default probability.
- Employment stability influences repayment reliability.
- Applicants requesting high loan amounts relative to income exhibit elevated risk.
- Credit utilization behavior contributes significantly to predictive performance.

---

# Business Recommendations

Based on the analysis, several operational recommendations were proposed:

- Implement stricter credit score thresholds
- Improve debt-to-income monitoring
- Introduce additional review for high-risk applicants
- Optimize marketing toward lower-risk customer groups
- Develop flexible repayment strategies for borderline applicants

These strategies can support:
- Reduced default rates
- Improved profitability
- Better portfolio stability

---

# Visualizations Included

The notebook includes:

- Correlation heatmaps
- Distribution analysis
- Income vs interest rate trends
- Feature importance analysis
- Classification evaluation metrics

---

# Future Improvements

Potential future enhancements include:

- Hyperparameter tuning
- Ensemble learning optimization
- Time-series behavioral analysis
- External credit bureau integration
- Real-time loan scoring systems
- Advanced neural network models

---

# Files Included

## Notebook
- End-to-end loan default analytics workflow

## Dataset
- Loan applicant and credit behavior dataset

---

# Disclaimer

This project was developed as part of an academic business analytics study focused on loan default prediction and financial risk assessment. The repository primarily showcases the analytical workflow, preprocessing pipeline, predictive modeling, and business insights generated during the analysis.

---

# Author

Faiz Nizamuddin Karol

LinkedIn: https://linkedin.com/in/faiz-karol
