# Repayment-Schedule-RPS-Normal-Loan

Steps Followed to Calculate Repayment Schedule
1. Import required Libraries like Pandas, datetime, etc.
2. Read data from excel/csv file
3. Check the sample data and datatypes
4. Calculate EMI using below formula -
    emi = round((loan_amt*roi_monthly*pow(1+roi_monthly,Tenure_yr*12)/(pow(1+roi_monthly,Tenure_yr*12) -1)),2) 
