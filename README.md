# Data Preparation for the UCI Heart Disease Dataset

This notebook walks through the step-by-step data preparation process for the "processed.cleveland.data" file from the UCI Machine Learning Repository.

## **The main preparation tasks are**:

1.  **Load Data:** Load the dataset from the web and assign the correct column names.
2.  **Handle Missing Values:** The dataset uses `'?'` for missing data. We will replace these and impute them.
3.  **Transform Target Variable:** Convert the multi-class target (0-4) to a binary target (0 vs. 1).
4.  **Encode & Scale Features:** Use `ColumnTransformer` to properly one-hot encode categorical features and scale numerical features.
