# Bank Marketing Prediction

This project builds a machine learning model to predict whether a bank customer will subscribe to a term deposit based on demographic, financial, and marketing campaign information.

The goal of this project is to demonstrate a complete machine learning workflow including data preprocessing, feature engineering, model training, and model evaluation using Python and Scikit-Learn.

---

## Project Overview

Banks often run marketing campaigns to promote financial products such as term deposits. Predicting which customers are more likely to subscribe can help improve campaign efficiency and reduce marketing costs.

This project uses a classification approach to predict customer subscription outcomes.

---

## Dataset

The dataset used in this project is the **Bank Marketing dataset**, which contains information about customer demographics, financial attributes, and past marketing interactions.

### Features include

- Age
- Job
- Marital status
- Education
- Balance
- Loan status
- Contact type
- Campaign history
- Previous contact information
- Marketing campaign details

### Target Variable

`deposit`

- **Yes** → Customer subscribed to the term deposit  
- **No** → Customer did not subscribe

---

## Machine Learning Workflow

The project follows a standard machine learning pipeline:

1. Data loading
2. Handling missing values
3. Encoding categorical features
4. Feature scaling
5. Feature engineering
6. Train-test split
7. Model training
8. Model evaluation

---

## Data Preprocessing

Several preprocessing techniques were applied:

- Replaced `"unknown"` values with missing values
- One-Hot Encoding for categorical features:
  - job
  - marital
  - contact
  - education
- Ordinal Encoding for the **month** feature
- Standard scaling for numerical variables
- Feature engineering for campaign history variables
- Handling missing values using imputation

---

## Models Implemented

Two machine learning models were trained and compared:

### Logistic Regression
Used as a baseline linear classification model.

### Decision Tree Classifier
A tree-based model capable of capturing nonlinear relationships in the data.

Both models were implemented using **Scikit-Learn**.

---

## Model Evaluation

Model performance was evaluated using:

- Accuracy Score
- ROC Curve
- ROC-AUC Score
- Precision-Recall Curve

These evaluation techniques help analyze model performance and compare different models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## Results

Both models successfully learned patterns from the dataset.  
Performance comparison was visualized using accuracy charts and ROC curves.

---

## Future Improvements

Possible improvements include:

- Hyperparameter tuning using GridSearchCV
- Testing additional models such as Random Forest or Gradient Boosting
- Feature selection techniques
- Cross-validation for more reliable evaluation

---

## Author

**Ridima Jain**
