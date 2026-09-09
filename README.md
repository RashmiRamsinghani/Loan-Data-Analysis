# Loan Approval Prediction

## Objective

To analyse loan applicant data and build a machine learning model to predict loan approval outcomes based on applicant and loan-related characteristics.

## Dataset

The dataset contains 614 loan applications and 13 variables covering:
- Applicant demographics
- Applicant and co-applicant income
- Loan amount and loan term
- Credit history
- Property area
- Loan approval status

## Data Processing

- Identified and handled missing values using mode and median imputation
- Encoded categorical variables into numerical values
- Converted the loan approval status into a binary variable
- Standardized selected numerical features
- Explored relationships between applicant characteristics and loan approval outcomes using visualizations

## Modelling

Four classification models were compared using 5-fold cross-validation:

- Logistic Regression
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Random Forest

### Cross-Validation Results

| Model | Mean Accuracy |
|---|---:|
| Support Vector Classifier | 80.95% |
| Logistic Regression | 80.46% |
| Random Forest | 78.99% |
| K-Nearest Neighbors | 72.80% |

The Support Vector Classifier achieved the highest mean cross-validation accuracy and was selected as the final model.

## Model Evaluation

The final Support Vector Classifier achieved approximately **80.65% accuracy on the test set**.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project File

The complete analysis and machine learning implementation are available in the Jupyter Notebook:

`Loan_approval (1)(1).ipynb`
