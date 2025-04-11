# Iranian-Telecom-Churn-Prediction

This repository contains a machine learning project focused on predicting customer churn in the Iranian telecom industry using classification techniques and handling class imbalance with sampling strategies.

## Overview

The objective of this project is to accurately predict whether a customer is likely to churn based on usage patterns and demographic features. The project involves data preprocessing, feature selection, model training, performance evaluation, and comparison across various resampling techniques.

## Project Link

You can access the full analysis and visualizations in the Jupyter Notebook available in this repository.

**Medium Article**: [Coming Soon]

## Project Features

The project includes the following major components:

- **Data Exploration and Cleaning**: Comprehensive EDA to understand data distributions, correlations, and missing values.
- **Class Imbalance Handling**: Techniques like SMOTE and under-sampling were used to tackle the severe class imbalance.
- **Model Building**: Training various classification models including:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - XGBoost
- **Performance Metrics**: Evaluation using Accuracy, Precision, Recall, and F1-score, particularly focusing on the minority class (churned customers).
- **Model Comparison**: An in-depth comparison of models trained on original vs resampled data to select the best performing approach.

## Dataset

The dataset used is derived from an Iranian telecom dataset, containing customer attributes such as:

- Subscription Length  
- Age  
- Frequency of Use  
- Call Failures  
- Distinct Numbers Called  
- Customer Value  
- And others...

The target variable is **Churn**, indicating whether a customer left the service or not.

## Key Findings

- Logistic Regression struggled with recall on imbalanced data.
- SMOTE significantly improved minority class recall.
- **XGBoost with SMOTE** emerged as the top performer with:
  - Accuracy: 97%
  - Precision: 89%
  - Recall: 95%
  - F1-score: 92%

## How to Use

To explore or run this project:

1. Clone or download this repository
2. Set up and activate a Python virtual environment
3. Install the required packages listed in `requirements.txt`
4. Place the dataset in the designated `data` folder
5. Open and run the Jupyter Notebook to see the analysis and results

---

Feel free to fork the repo and build on top of this work for more advanced use cases or deeper telecom analytics.
