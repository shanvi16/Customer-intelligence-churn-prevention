# Customer Intelligence & Churn Prevention System

## Overview
This project analyzes customer data and builds machine learning
models to identify customers who may leave a telecom service.

## Dataset
IBM Telco Customer Churn dataset.
The dataset contains customer demographics, subscribed services,
account information, and churn labels.

## Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Work Completed
- Data loading and exploratory data analysis
- Missing-value investigation and preprocessing
- Categorical feature encoding
- Logistic Regression model
- Decision Tree model
- Evaluation using Accuracy, Precision, Recall, F1 Score, and ROC-AUC
- Model coefficient visualization
- Model comparison chart and results table

## Model Evaluation
See `model_comparison_results.csv` for the measured scores
and `model_comparison.png` for the comparison chart.

## Important Note
The reported metrics are based on the current test split.
Further validation is needed before real-world deployment.
Model predictions indicate associations and do not establish causation.

## Future Improvements
- Tune models and decision thresholds
- Validate performance on unseen data
- Develop customer-risk segmentation
- Build an interactive Streamlit dashboard
- Add business recommendations and deployment documentation
