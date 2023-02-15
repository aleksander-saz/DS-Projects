# Project 2  - Survey of the reliability of the bank clients

Based on the provided data from client (Credit department of the Bank) it's required to analyze the data using pandas library and summarize how does the marital status and quantity of child are influence on the payment of outstanding fees in the specified duration in credit contract. For the proper data analysis it's required to complete data preparation - fill up the nulls, process the duplicates and add columns for categorization of income and categorization of credit propose using lemmatization.

Additionally it's required to answer on following questions:

- Does the presence of a child has affect payment of outstanding fees in the specified duration in the credit contract?
- Does the marital status has affect on payment of outstanding fees in the specified duration in the credit contract?
- Does the income grade has affect on payment of outstanding fees in the specified duration in the credit contract?
- How does the different credit purpose affect on the payment of the outstanding fees in the specified duration in the credit contract?

**Dataset description**
Dataset has 21525 rows and  11 following columns: 
- children (quantity of child in family);
- days_employed (work experience, days);
- dob_years (client age);
- education;
- education_id;  
- family_status;
- family_status_id;   
- gender; 
- income_type (type of occupation); 
- debt (previous records on debts);
- total_income  (monthly income);
- purpose (credit purpose);
