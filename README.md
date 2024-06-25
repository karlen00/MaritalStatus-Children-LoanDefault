# MaritalStatus-Children-LoanDefault

### Project to Assess the Effect of Marital Status and Number of Children on the Probability of Loan Default

#### Project Description

This project aims to analyze the influence of marital status and number of children on the probability of loan default. The data used is the creditworthiness data of bank customers. The report generated will be used as a consideration in making credit assessments for prospective borrowers.

#### Data Used

The data used in this project is contained in the file `credit_scoring_eng.csv`. The description of the columns in the dataset is as follows:
- `children`: number of children in the family
- `days_employed`: how long the customer has been employed
- `dob_years`: age of the customer
- `education`: education level of the customer
- `education_id`: identifier for the education level of the customer
- `family_status`: marital status of the customer
- `family_status_id`: identifier for the marital status of the customer
- `gender`: gender of the customer
- `income_type`: type of income of the customer
- `debt`: whether the customer has defaulted on a loan
- `total_income`: monthly income
- `purpose`: purpose of the loan

#### Project Steps

1. **Read Data and General Information**
   - Read the `credit_scoring_eng.csv` file and display general information about the data.

2. **Data Preprocessing**
   - Identify and fill in missing values.
   - Convert real number data types to integer types.
   - Remove duplicate data.
   - Categorize data.
   
   Explanation:
   - **Missing Values**: Identify missing values, possible causes, and the method used to fill in the missing values.
   - **Duplicate Data**: Method of identifying and removing duplicate data and the reason for using it.
   - **Data Types**: Method of changing data types and the reason for using it.
   - **Data Categorization**: Explanation of the categories created and the reason for creating them.

3. **Data Analysis**
   - Answer the following questions:
     - Is there a relationship between having children and the probability of defaulting on a loan?
     - Is there a relationship between marital status and the probability of defaulting on a loan?
     - Is there a relationship between income level and the probability of defaulting on a loan?
     - How does the purpose of the loan affect the probability of defaulting on a loan?
   - Present the analysis results and explain the findings.

4. **Conclusion**
   - Write a conclusion summarizing the overall analysis conducted.

### Steps to Complete the Project

1. **Read Data and General Information**
   - Read the file `credit_scoring_eng.csv` and display general information about the data.

2. **Data Preprocessing**
   - Identify and fill in missing values.
   - Convert real number data types to integer types.
   - Remove duplicate data.
   - Categorize data.

3. **Data Analysis**
   - Answer specific questions regarding the relationships between various factors (such as children, marital status, income level, loan purpose) and loan default probability.
   - Present the results of the analysis and provide explanations for the findings.

4. **Conclusion**
   - Summarize the overall analysis and provide final conclusions.
