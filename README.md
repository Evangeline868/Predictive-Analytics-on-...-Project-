# Predictive Analytics in the Tourism & Hospitality Industry  
**ISOM 835 – Predictive Analytics and Machine Learning (Spring 2025)**  
**Suffolk University | Instructor: Dr. Hasan Arslan**

## Project Summary

This project applies predictive analytics and machine learning models to a real-world dataset from the global tourism and hospitality industry. Using advanced Python tools, we aim to explore customer behavior, predict hotel revenue, customer return likelihood, and classify hotel categories based on spending, satisfaction, and service quality.

## Objectives

- Clean and preprocess real-world tourism industry data
- Develop and evaluate multiple predictive models
- Answer key business questions relevant to hotel revenue and customer retention
- Visualize model performance and dataset structure
- Reflect on model interpretability and ethical implications

## Dataset Description

- **Source**: [Kaggle Dataset - Tourism & Hospitality Industry Analysis](https://www.kaggle.com/datasets/smithmurphy/tourism-and-hospitality-industry-analysis-dataset)
- **Size**: 500 rows × 23 columns
- **Features Include**: tourist satisfaction, eco-tourism revenue, hotel ratings, country/city, spending behavior, infrastructure scores, etc.

## Tools & Libraries Used

- **Languages**: Python 3
- **Platforms**: Google Colab + GitHub
- **Libraries**:  
  - `pandas`, `numpy` – data cleaning and wrangling  
  - `scikit-learn` – modeling and evaluation  
  - `xgboost` – advanced boosting models  
  - `seaborn`, `matplotlib` – data visualization  

## Business Questions

1. **What will be the tourism revenue from a given customer segment?**  
   - Modeled as a regression task.

2. **Will a customer return (or churn) based on satisfaction and experience?**  
   - Binary classification.

3. **What type of hotel (budget, luxury, midrange) does a booking fall into?**  
   - Multiclass classification.

##  Predictive Models Applied

Each question uses at least 3 models. Examples include:
- `Lasso Regression`
- `Decision Tree`
- `Gradient Boosting`
- `XGBoost`
- `Naive Bayes`
- `Random Forest`

Models were evaluated using:
- **Regression Metrics**: RMSE, R²
- **Classification Metrics**: Accuracy, F1 Score, ROC AUC
- **Visuals**: confusion matrices, residual plots, heatmaps



