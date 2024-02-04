# Fintech Loan Performance Analysis

## Project Overview

This project aims to analyze and improve the performance of a customer loan product for a fintech company. The provided dataset (`credit_default.json`) includes various customer attributes, such as age, sex, job, housing status, purpose of the loan, and financial metrics. The ultimate goal is to build a predictive model to identify customers at risk of default.

## Problem Statement

Formulate the problem statement: Improve the performance of the customer loan product by analyzing customer attributes and building a predictive model to identify potential defaults.

## Data Science Process

1. **Descriptive Analysis:**
   - Explore and analyze the dataset to gain insights into customer characteristics.
   - Understand the distribution of key features.

2. **Attribute Influence on Default:**
   - Conduct statistical tests (t-test) to identify attributes significantly influencing defaults.
   - Example: Test the significance of average loan duration for default and non-default customers.

3. **Classification Model:**
   - Preprocess data by handling missing values and encoding categorical variables.
   - Build a RandomForestClassifier model.
   - Perform hyperparameter tuning using GridSearchCV.

4. **Model Evaluation:**
   - Assess the model's accuracy and provide a classification report.

## File Structure

- `credit_default.json`: The dataset in JSON format.
- `Fintech_Loan_Performance.ipynb`: Jupyter Notebook containing the Python code for the analysis.

## Getting Started

1. Clone the repository.
2. Open and run the Jupyter Notebook (`Fintech_Loan_Performance.ipynb`).

## Conclusion

The project involves a comprehensive analysis of customer loan data, including descriptive analysis, statistical tests to identify influential attributes, and the development of a predictive model. The results aim to provide actionable insights for the fintech company to enhance the performance of its loan products.

Feel free to explore the notebook for detailed code implementation and analysis.
