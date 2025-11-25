# Credit Risk Prediction

## Objective
Predict whether a loan applicant is likely to default on a loan using historical loan data.

## Approach
1. **Data Loading & Cleaning**: Loaded the Loan Prediction Dataset and handled missing values using median (for numeric columns) and mode (for categorical columns).  
2. **Exploratory Data Analysis (EDA)**: Visualized key features like LoanAmount, ApplicantIncome, and Education to understand distributions and patterns.  
3. **Model Training**: Trained two classification models – Logistic Regression and Decision Tree – to predict loan default.  
4. **Model Evaluation**: Evaluated the models using accuracy and confusion matrix to measure prediction performance.

## Results & Insights
- Logistic Regression and Decision Tree models achieved strong accuracy on test data.  
- Key factors influencing loan approval include applicant income, education, and loan amount.  
- The models can help financial institutions identify high-risk applicants and reduce loan defaults.
