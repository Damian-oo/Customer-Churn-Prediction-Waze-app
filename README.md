# Customer Churn Prediction - Waze app

This project aims to predict customer churn using machine learning techniques. The dataset contains customer information from last month such as number of sessions, acitivity days in app, driving days, kms and minutes. Other variables contain device type as well as information about how long a particular user has been using Waze app. The model should help businesses retain customers by identifying those users that are likely to leave, hence improving retention and helping app grow.


## Dataset information

- **Source:** Kaggle - Waze Customer Churn Dataset
- **Size:** 14,999 rows × 13 columns
- **Target Variable:** Label (Retained/Churned)
- **Key Features:** 
  - `sessions` (The number of occurrence of a user opening the app during the month)
  - `activity_days` (Number of days the user opens the app during the month)
  - `n_days_afetr_onboarding` (The number of days since a user signed up for the app)
- **Preprocessing Steps:**
  - Handled missing values
  - Encoded categorical variables


## Project Workflow
1. **Data Collection:** Gather dataset from Kaggle.
2. **Data Cleaning:** Handle missing values, Encoded categorical variable
3. **Exploratory Data Analysis (EDA):** Identify patterns & correlations.
4. **Feature Engineering:** Normalize and encode categorical features.
5. **Condunct Hypothesis Tests:**: Look for statistically significant relationships.
6. **Model Training:** Train models (Logistic Regression, Random Forest, XGBoost).
7. **Evaluation:** Compare models using Accuracy, Precision, Recall, f1-score.
8. **Deployment:** Choose one champion model and evaluate it on unseen data.
