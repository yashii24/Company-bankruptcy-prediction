# Company Bankruptcy Prediction using Machine Learning

## Overview

This project predicts whether a company is likely to go bankrupt based on its financial indicators using Machine Learning classification models.

The project includes data preprocessing exploratory data analysis model training model evaluation and model comparison to identify the best performing model.

---

## Objective

Develop a machine learning model that can classify companies into:

- Healthy Company
- Bankrupt Company

This project can assist in financial risk assessment and decision making.

---

## Dataset

- Total Records: 10,000
- Features: 30 Financial Indicators
- Target Variable: class

Class Distribution

- Healthy Companies: 9,500
- Bankrupt Companies: 500

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab
- GitHub

---

## Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Scaling
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Save Best Model

---

## Models Trained

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score

---

## Results

All evaluated models achieved excellent performance on the provided dataset.

The Random Forest model was selected as the final model for deployment due to its strong performance and ability to capture complex relationships among financial indicators.

---

## Feature Importance

Top financial indicators contributing to bankruptcy prediction include:

- Current Assets / Total Liabilities
- Short Term Liabilities / Total Assets
- Profit on Sales
- Equity Fixed Assets
- Working Capital

---

## Repository Structure

```text
company-bankruptcy-prediction/
│
├── data/
├── notebooks/
├── models/
├── images/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Future Improvements

- Hyperparameter tuning
- Cross Validation
- XGBoost implementation
- Streamlit Web Application
- Cloud Deployment

---

## Author

Yashi Kardam
