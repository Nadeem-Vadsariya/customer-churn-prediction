# Telecom Customer Churn Prediction & Retention Analysis

## About the Project

Customer retention is a major challenge for telecom companies. Losing customers doesn't just affect the customer base; it can also impact business revenue.

I worked on this project to understand why customers leave a telecom service and whether machine learning can help identify those customers before they decide to leave.

Using the IBM Telco Customer Churn dataset, I explored customer information, prepared the data and built machine learning models to predict customer churn.

## What I Worked On

I started by exploring the dataset to understand the available customer information and identify any data quality issues.

The project involved:

- Exploring and understanding the dataset.
- Cleaning missing and inconsistent values.
- Performing exploratory data analysis (EDA).
- Creating new features to improve the analysis.
- Preparing numerical and categorical data for machine learning.
- Splitting the data into training and testing sets.
- Building and evaluating different classification models.
- Comparing model performance.
- Experimenting with different prediction thresholds.
- Identifying the features that contribute most to the model's predictions.

## Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset

I used the IBM Telco Customer Churn dataset, which contains information about approximately 7,043 telecom customers.

It includes details such as customer tenure, monthly charges, services, contract types and payment methods.

The target variable is **Churn**, which indicates whether a customer left the company.

## Model Development & Results

I experimented with three model configurations to compare their performance.

| Model | Accuracy | Churn Recall | Churn F1-score |
|---|---:|---:|---:|
| Logistic Regression | 79.91% | 52% | 58% |
| Balanced Logistic Regression | 73.31% | 79% | 61% |
| Random Forest | 78.00% | 47% | 53% |

Balanced Logistic Regression achieved the highest recall for the churn class.

I also experimented with prediction thresholds to understand how changing the threshold affects the model's ability to identify customers who are likely to leave.

## What I Found

During the feature importance analysis, I found that the following features had the highest importance in the Random Forest model:

- Total Charges
- Monthly Charges
- Customer Tenure
- Contract Type
- Payment Method
- Number of Services

These findings helped me understand which customer characteristics were most useful for predicting churn.

## Business Recommendations

Based on the analysis, telecom companies could consider:

- Paying closer attention to customers with shorter tenure.
- Reviewing pricing for customers with higher monthly charges.
- Offering retention plans to month-to-month contract customers.
- Improving the experience of customers using electronic check payments.
- Encouraging customers to explore additional support services.

These recommendations could help businesses develop more targeted customer retention strategies.

## Conclusion

This project gave me practical experience working through a complete machine learning workflow, from data cleaning and exploratory analysis to model development and evaluation.

One of the biggest takeaways was that accuracy alone doesn't tell the whole story. In a customer churn problem, identifying customers who are actually likely to leave can be just as important.

I enjoyed working on this project because it allowed me to connect machine learning results with a real business problem.
