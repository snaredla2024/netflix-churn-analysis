# netflix-churn-analysis
"Churn" means a customer cancels their subscription. This project answers three questions that often contribute to churning subscriptions of Netflix.
Question 1: How many customers churn overall?
Question 2: Which types of customers churn the most? 
Question 3: What could Netflix possibly do to reduce the churn rate? 
----------------------------------------------------------------------
The Data 
An Excel file from Kaggle is used for this project. In this file, one row is dedicated to one customer. The columns used in this project are: 
- churn status (yes/no) - did the customer cancel?
- subscription plan - which plan is a customer subscribed to?
- subscription length - how long have they been a customer of Netflix?
- daily watch time(hours)- what is their watch time per day?
- customer satisfaction score (1-10)- how happy are they with Netflix?
-----------------------------------------------------------------------
How the code works: 
Step 1: Load the data. Upload the Excel file to Google Colab and read it into a pandas DataFrame. Print the first 10 rows, the number of customers, and the column names to make sure it loaded correctly. 
Step 2: Churn overview. Count how many customers churned vs. stayed and calculate the overall churn rate: Churn rate = churned customers / total customers x 100. 
Step 3: Find Patterns. Customers are grouped into categories, and then the churn rate is calculated for each group. 
Step 4: Churn rates are visualized through three graphs. (pie chart, bar chart by subscription plan, and bar chart by daily watch time)
Step 5: Recommendations. A short written report that summarizes the findings and proposes ideal solutions.
--------------------------------------------------------------------------------------------------
Key Findings: 
- Basic plan churn rate is 45%
- New customer churn rate is 58% in the first 6 months, compared to long-term customers who only have a 15% churn rate.
- Heavy watchers have a 5% churn rate, while customers who have 0-2 hours of watch time have a 73% churn rate.
- Satisfied customers have a 2% churn and unsatisfied customers have an 85% churn rate. 
