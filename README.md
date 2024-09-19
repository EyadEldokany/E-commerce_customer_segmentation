E-commerce Customer Segmentation Project
Project Overview
This project aims to perform customer segmentation using an e-commerce dataset, which consists of five interrelated tables containing customer demographic, transactional, branch, and merchant data. The goal is to build a dashboard for stakeholders and identify distinct customer groups through clustering, enabling data-driven marketing and customer loyalty strategies.

Key Objectives:
Dashboard for Stakeholders:
Visualize key insights such as customer demographics, coupon usage trends, and top-performing cities/branches.
Customer Segmentation:
Use unsupervised learning models to group customers based on their transactional behavior and demographics, providing recommendations for targeted marketing.
Dataset Overview
The dataset comprises five tables:

Customers Table
Contains customer demographic information:

customer_id: Unique identifier for each customer.
join_date: Date the customer joined.
city_id: ID representing the customer's city.
gender_id: ID representing the customer's gender.
Genders Table
Contains gender details:

gender_id: Unique identifier for each gender.
gender_name: Name of the gender (e.g., male, female).
Cities Table
Contains city details:

city_id: Unique identifier for each city.
city_name: Name of the city.
Transactions Table
Contains coupon transaction details:

transaction_id: Unique identifier for each coupon transaction.
customer_id: ID of the customer who performed the transaction.
transaction_date: Date the coupon was claimed.
transaction_status: Status of the coupon (e.g., claimed, burnt).
burn_date: Date the coupon was burnt.
branch_id: ID of the branch where the coupon was burnt.
Branches Table
Contains branch and merchant details:

branch_id: Unique identifier for each branch.
merchant_id: ID of the merchant who owns the branch.
Merchants Table
Contains merchant details:

merchant_id: Unique identifier for each merchant.
merchant_name: Name of the merchant.
