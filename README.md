# Life_Insurance-_SQL-_Project
SQL project analyzing life insurance customer and policy data
# Life Insurance SQL Project

This project analyzes life insurance customer and policy data using SQL.

## Tables Used
- Customer
- Policies
- Policy_Holders

## SQL Concepts Used
- SELECT
- INSERT
- JOIN
- GROUP BY
- Aggregate Functions

## Example Query
SELECT c.customer_name, p.policy_name
FROM policy_holders ph
JOIN customer c ON ph.customer_id = c.customer_id
JOIN policies p ON ph.policy_id = p.policy_id;
