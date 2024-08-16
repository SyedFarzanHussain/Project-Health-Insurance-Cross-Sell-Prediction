# Health Insurance Cross Sell Prediction

## Overview

This project aims to predict whether individuals with health insurance would be interested in purchasing vehicle insurance. The project was part of a Kaggle competition that posed a highly imbalanced classification problem, requiring robust machine learning techniques to ensure reliable predictions.

## Objective

The goal is to develop a predictive model that identifies potential customers for vehicle insurance among existing health insurance holders. The focus was on building models that effectively handle class imbalance and produce accurate predictions.

## Key Responsibilities

### Data Preprocessing

- **Missing Value Handling**: Managed missing values to maintain data integrity.
- **Feature Engineering**: Created new features and modified existing ones to improve model performance.
- **Categorical Encoding**:
  - Applied **One-Hot Encoding** and **Label Encoding** for categorical variables.
- **Feature Scaling**: Standardized numerical features for uniformity across models.
- **Data Balancing**: Applied techniques like **Random Under-sampling** to balance the dataset, addressing the issue of class imbalance.

### Model Development

- **Model Selection**: Evaluated multiple machine learning models, including:
  - Logistic Regression
  - Decision Trees
  - Random Forests
  - Gradient Boosting Machines (XGBoost)
- **Hyperparameter Tuning**: Conducted **Grid Search** to fine-tune model hyperparameters and improve performance.

### Model Evaluation

- **Evaluation Metric**: Assessed model performance using the **ROC-AUC** (Receiver Operating Characteristic - Area Under the Curve) metric, which is well-suited for imbalanced datasets.
- **Model Performance**:
  - Achieved significant performance improvements using Gradient Boosting Machines, which excelled in handling complex patterns within the data.
  - The final model demonstrated strong predictive performance with a high ROC-AUC score, indicating its ability to effectively distinguish between customers interested and not interested in purchasing vehicle insurance.

## Outcome

- Successfully developed a predictive model that identifies potential customers for vehicle insurance among existing health insurance holders.
- Achieved a high ROC-AUC score, demonstrating the model's robustness and effectiveness.

  ## Dataset

The dataset used in this project can be found on Kaggle: [Health Insurance Cross Sell Prediction](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction).
