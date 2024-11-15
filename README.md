![AdobeStock_816783774](https://github.com/user-attachments/assets/47446e75-b4f1-4f09-b28b-cd7753cd9f3b)
# Loan Approval Prediction

This project aims to predict loan approval status based on various attributes of the applicants. The dataset used in this notebook includes several features that provide information about the applicants' personal and financial details.

## Dataset

The dataset contains the following columns:

- **id:** Applicant ID
- **person_age:** Age of the applicant
- **person_income:** Income of the applicant
- **person_home_ownership:** Home ownership status of the applicant
- **person_emp_length:** Employment length (in years) of the applicant
- **loan_intent:** Intent of the loan
- **loan_grade:** Grade assigned to the loan
- **loan_amnt:** Amount of the loan
- **loan_int_rate:** Interest rate of the loan
- **loan_percent_income:** Percentage of the applicant's income that the loan amount constitutes
- **cb_person_default_on_file:** Historical default status (if the applicant has defaulted before)
- **cb_person_cred_hist_length:** Length of the applicant's credit history
- **loan_status:** Status of the loan (0: No, 1: Yes)

## Steps Performed

### 1. Exploratory Data Analysis (EDA)
**Objective:** Understand the data, identify patterns, and uncover initial insights.

**Actions:** Visualized distributions of key features, plotted correlations, and examined outliers.

### 2. Data Cleaning
**Objective:** Prepare the data for analysis by handling missing values and correcting inaccuracies.

**Actions:** Filled or dropped missing values, corrected data types, and standardized categorical values.

### 3. Feature Engineering
**Objective:** Enhance the dataset with additional information that may improve the model's performance.

**Actions:** Created new features such as ratios and interaction terms, transformed categorical features into numerical formats using one-hot encoding.

### 4. Data Validation
**Objective:** Ensure data quality and consistency after cleaning and feature engineering.

**Actions:** Verified the absence of missing values, checked for duplicates, and ensured feature distributions were reasonable.

### 5. Model Creation
**Objective:** Build and evaluate machine learning models to predict loan approval status.

**Models Used:**
- **Random Forest:** Built a Random Forest classifier to capture non-linear relationships and feature interactions.
- **XGBoost:** Implemented XGBoost for its robustness and performance on structured data.
- **Comparison:** Evaluated and compared the performance of both models using metrics like accuracy, precision, and recall.

### 6. Model Evaluation
**Objective:** Assess the performance of the trained models and refine them if necessary.

**Actions:** Used cross-validation, hyperparameter tuning, and compared metrics to select the best-performing model.

### 7. Final Model Training
**Objective:** Train the selected model on the full training dataset for final evaluation.

**Actions:** Retrained the best model on the entire training set and evaluated it on the test set to determine the final accuracy.
