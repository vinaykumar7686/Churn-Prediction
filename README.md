# Churn-Prediction

This is my ML project that aims at building a Model that predicts how likely is a customer to churn.

## Problem Statement

Customer Churn Prediction:
A Bank wants to take care of customer retention for its product: savings accounts. The bank wants you to identify customers likely to churn balances below the minimum balance. You have the customers information such as age, gender, demographics along with their transactions with the bank.
Your task as a data scientist would be to predict the propensity to churn for each customer.
<br><br>
Data Dictionary
<br>
There are multiple variables in the dataset which can be cleanly divided into 3 categories:<br><br>
I. Demographic information about customers
•	customer_id - Customer id <br>
•	vintage - Vintage of the customer with the bank in a number of days <br>
•	age - Age of customer <br>
•	gender - Gender of customer<br> 
•	dependents - Number of dependents <br>
•	occupation - Occupation of the customer <br>
•	city - City of the customer (anonymized) <br>
<br>
II. Customer Bank Relationship<br>
•	customer_nw_category - Net worth of customer (3: Low 2: Medium 1: High) <br>
•	branch_code - Branch Code for a customer account <br>
•	days_since_last_transaction - No of Days Since Last Credit in Last 1 year <br>
<br>
III. Transactional Information<br>
•	current_balance - Balance as of today <br>
•	previous_month_end_balance - End of Month Balance of previous month <br>
•	average_monthly_balance_prevQ - Average monthly balances (AMB) in Previous Quarter <br>
•	average_monthly_balance_prevQ2 - Average monthly balances (AMB) in previous to the previous quarter <br>
•	current_month_credit - Total Credit Amount current month <br>
•	previous_month_credit - Total Credit Amount previous month <br>
•	current_month_debit - Total Debit Amount current month <br>
•	previous_month_debit - Total Debit Amount previous month <br>
•	current_month_balance - Average Balance of current month <br>
•	previous_month_balance - Average Balance of previous month <br>
•	churn - Average balance of customer falls below minimum balance in the next quarter (1/0) <br>
