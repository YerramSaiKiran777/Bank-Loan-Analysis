# Bank-Loan-Analysis
This repository is related to the analysis of loans issued by bank. Used SQL to examine the data and derive useful insights from it that helps the bank to monitor it's lending activities and risk assessment.

# Task:
Examine the bank's loans data provided by the client to draw useful information that helps the bank to understand it's lending activities, fundings, credit risks and the repayment behaviour to take data-driven actions and design operational strategies to mitigate the risk, improve the profitability and maintain the financial health of the bank.

# Dataset Description:
-- The dataset provided contains 38K records
-- Each record refers to an approved loan and identified by a unique id
-- Provided cols, address_state, application type, loan_amount, term and purpose add more details to each of the loan
-- Grades and sub_grade details are useful to acknowledge the risk associate with each loan
-- Loan_status field carries details whether a loan is currently active, completed or charged off.

# Details of the project:
- Created a comprehensive schema and imported dataset seamlessly into it.
- Analysed loan_status field to find the good loans and bad loans percentage.
- Examined:
        -- issue-date field to find the monthly trend of loan lending’s
        -- purpose field to identify the purpose with highest no of loans taken
        -- subgrade field to find the most risk associated category of loans issued.
- Implemented SQL concepts such as:
       -- group by statements
       -- date functions
       -- aggregation functions
       -- CTEs
       -- window functions
       -- sub-queries and 
       -- stored procedures to address business problems.
- Gained understanding of domain specific terms like 
       -- Debt-to-Income ratio
       -- credit risk
       -- grades and subgrades 
       -- risk analysis that helped to better understand the data and perform required analysis.


# Insights from Analysis:
-- Witnessed an increase of 13.04% in issued loans for latest month compared to previous month
-- 83.33 % of approved loans have completely paid the amount while a significant portion of 13.82% of loans were charged-off and the rest 2.85% of the loans are currently active.
-- 86.18% of loans are found to be good-loans and the remaining 13.82% of the loans are bad-loans
-- Among all the loan purposes, Debt consolidation is identified to be the top purpose with max no of loan applications (18214) and funding amount (232.46M)  
-- 'G2' is the most risk associated category with 35.9% charged off loans at subgrade level 


# Source: 
This project is available in DataTutorials youtube channel
link: https://www.youtube.com/watch?v=bakn6HGemyM
Note: I have used this dataset to frame few own questions and perform my own analysis. So, the questions and the SQL queries mentioned in my analysis may differ from source content.

Thanks for reading!
