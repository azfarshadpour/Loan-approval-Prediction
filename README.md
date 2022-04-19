# Loan-approval-Prediction
In this project, the loan eligibility process has been automated based on customer details that are provided as online application forms are being filled. This process has been done by analyzing, cleaning, feature engineering the data, and finally creating a predictive model with logistic regression technique and deploying the model. 
You can find the dataset [here](https://drive.google.com/file/d/1h_jl9xqqqHflI5PsuiQd_soNYxzFfjKw/view?usp=sharing).

# Variable's Descriptions
Loan_ID: 	Unique Loan ID
Gender: 	Male/ Female
Married: 	Applicant married (Y/N)
Dependents: 	Number of dependents
Education: 	Applicant Education (Graduate/ Under Graduate)
Self_Employed: 	Self employed (Y/N)
ApplicantIncome: 	Applicant income
CoapplicantIncome: 	Coapplicant income
LoanAmount: 	Loan amount in thousands
Loan_Amount_Term: 	Term of loan in months
Credit_History: 	credit history meets guidelines
Property_Area: 	Urban/ Semi Urban/ Rural
Loan_Status: 	Loan approved (Y/N)

# Exploreed the problem in following stages

    Hypothesis Generation – understanding the problem better by brainstorming possible factors that can impact the outcome
    Data Exploration – looking at categorical and continuous feature summaries and making inferences about the data.
    Data Cleaning – imputing missing values in the data and checking for outliers
    Feature Engineering – modifying existing variables and creating new ones for analysis
    Model Building – making predictive models on the data
# Hypothesis Generation

### Possible Hypothesis
Which applicants are more likely to get a loan

1. Applicants having a credit history 
2. Applicants with higher applicant and co-applicant incomes
3. Applicants with higher education level
4. Properties in urban areas with high growth perspectives
