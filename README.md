# Credit-Card-Report-Dashboard-Project
--------------------------------------
# Project Overview – Credit Card Analysis Dashboard
===================================================
# This project consists of two integrated dashboards:

# 1. Credit Card Customer Report
  Focuses on customer demographics, revenue contribution, and behavior.
  Analyzes revenue trends by job type, income group, age group, education level, and states.
  Provides gender-based insights, showing nearly equal revenue contributions from male and female customers (~739M each).
  Identifies top-performing customer segments like businessmen, white-collar employees, and high-income groups.
  Tracks revenue trends across weeks, helping monitor seasonality.

# 2. Credit Card Transaction Report
  Focuses on transaction-level insights across card categories.
  Revenue: 55M, Transactions: 656K, Interest: 8M, Transaction Amount: 45M.
  Analyzes revenue & transactions by card type (Blue, Silver, Gold, Platinum) → Blue card dominates with 46M revenue.
  Shows revenue contribution by transaction mode (Swipe = 35M, Chip = 17M, Online = 3M).
  Breaks down spending patterns by expenditure categories → Bills (14M), Entertainment (10M), Fuel (9M), Grocery (9M).
  Tracks quarterly revenue vs transaction volume, showing steady growth till Q3 and slight dip in Q4.

# Key Insights
1.Customer Behavior
  Majority revenue comes from businessmen (17M) & white-collar employees (10M).
  Middle-aged customers (40–50 years) generate the highest revenue.
  High-income groups dominate spending, but medium & low-income groups also show significant contribution.
2.Transaction Patterns
  Blue cards are most used, followed by Silver. Gold & Platinum show minimal revenue contribution.
  Swipe transactions dominate (35M) over chip and online.
  Spending is highest on Bills, Entertainment, and Fuel.
3.Quarterly Trends
  Revenue stable (13–14M each quarter).
  Transaction volume peaked in Q3 (166.6K) before slightly declining in Q4.

# Business Impact
Helps banks identify profitable customer segments and focus on businessmen & white-collar professionals for premium offers.
Insights into expenditure categories support targeted marketing campaigns (e.g., fuel cashback, entertainment rewards).
Card category analysis shows need to promote Gold & Platinum cards since Blue dominates heavily.
Gender and age analysis enables personalized offers to improve engagement.

# Tools & Techniques Used
SQL → Data extraction & transformation (customer details, transactions, expenditure categories).
Excel → Data cleaning, formatting, initial pivot analysis.
Power BI → Dashboard creation, DAX measures (Revenue, Interest, Count), interactive filters for card type, gender, quarter, states.
