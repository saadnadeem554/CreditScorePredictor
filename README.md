# Credit Scoring Model Notebook

This notebook demonstrates the development of a credit scoring model to predict the creditworthiness of individuals based on historical financial data. It covers data preprocessing, model training, and evaluation using various machine learning algorithms.

## Contents

1. **Data Loading and Preprocessing**:
   - Loads the dataset from an Excel file (`CreditWorthiness.xlsx`).
   - Performs data preprocessing, including encoding categorical variables using techniques like One-Hot Encoding, Ordinal Encoding, and Label Encoding.
   - Scales numerical features using `StandardScaler` for normalization.

2. **Model Building**:
   - Utilizes several machine learning models for classification:
     - Logistic Regression
     - Decision Tree Classifier
     - Random Forest Classifier
     - Gradient Boosting Classifier
     - Support Vector Classifier (SVC)

3. **Model Evaluation**:
   - Evaluates each model using metrics such as accuracy score, confusion matrix, and classification report.
   - Compares the performance of different models to identify the best-performing model for predicting creditworthiness.

## Usage

To run this notebook, make sure you have the required libraries installed (`pandas`, `scikit-learn`, `openpyxl`, etc.) and the dataset file `CreditWorthiness.xlsx` in the same directory.

Open the notebook in Jupyter and execute the cells step-by-step to see the data preprocessing, model training, and evaluation processes.

## Conclusion

This notebook provides a comprehensive guide to building a credit scoring model using Python and various machine learning algorithms. It is useful for understanding how different models can be applied and compared for predicting credit risk.
