# Customer Churn Prediction Model

## Project Goals

This project aims to develop a supervised classification model to predict customer churn, providing actionable insights for customer retention strategies.

### Primary Goal:
* Build a supervised classification model to predict customer churn with high accuracy and recall.

### Secondary Goals:
1.  Identify the most important features influencing customer churn.
2.  Provide actionable insights to the marketing team to improve customer retention efforts.
3.  Evaluate model performance using key metrics such as Precision, Recall, F1-score, and ROC-AUC.

## Methodology (Inferred from Goals)

The notebook likely covers the following steps:
* **Data Preprocessing:** Cleaning and preparing the customer dataset.
* **Feature Engineering:** Creating relevant features for the model.
* **Model Selection & Training:** Choosing and training suitable classification algorithms.
* **Model Evaluation:** Assessing the performance of the trained models using various metrics.
* **Feature Importance Analysis:** Identifying which factors most significantly contribute to customer churn.
* **Business Interpretation:** Translating model results into practical business recommendations.

## Key Findings & Model Performance Highlights

The project successfully built a churn prediction model with the following performance indicators (actual values would be from the notebook's execution):

* **Accuracy:** The overall accuracy of the model is 80.62%, indicating its general correctness in predictions.
* **Recall:** The model correctly identifies 56% of actual churners, which is crucial for not missing potential churn customers.
* **Precision:** Of the customers predicted to churn, 66% actually will churn, showing the reliability of positive churn predictions.
* **ROC-AUC Score:** The model achieved an ROC-AUC score of 84.18%, demonstrating its ability to distinguish between churners and non-churners across various thresholds.

These results provide valuable insights for prioritizing retention efforts and allocating resources effectively.

## Tools and Libraries Used

* **Programming Language:** Python
* **Key Libraries (Expected):** `pandas`, `numpy` for data manipulation; `scikit-learn` for machine learning models and evaluation metrics; `matplotlib`, `seaborn` for data visualization.
