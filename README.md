# Banking Analysis Using MySQL

## Project Overview
This project focuses on analyzing banking data using MySQL. It uses a relational database to manage customer details, bank branches, employees, accounts, loans, and transactions.

The project demonstrates practical SQL skills used to retrieve, analyze, and summarize banking data for business insights.

## Tools Used
- MySQL
- MySQL Workbench
- SQL

## Database Tables
The project contains six tables:

1. **Customers** – Customer details, age, city, occupation, and join date.
2. **Branches** – Branch information, city, and manager name.
3. **Employees** – Employee details, job titles, salaries, and branch assignments.
4. **Accounts** – Account types, balances, opening dates, and status.
5. **Loans** – Loan amounts, interest rates, loan types, and loan status.
6. **Transactions** – Transaction dates, amounts, transaction types, and channels.

## SQL Concepts Covered
- Database and table creation
- Primary keys and foreign keys
- Data insertion
- SELECT, WHERE, and ORDER BY
- Aggregate functions: COUNT(), SUM(), and AVG()
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- Subqueries
- Window functions: RANK(), DENSE_RANK(), and ROW_NUMBER()
- Filtering and sorting banking records

## Business Questions Answered
- Which customers live in Chennai, ordered by age?
- Which accounts have balances above ₹100,000?
- How many customers are in each city?
- What is the average balance for each account type?
- Which branches have total account balances above ₹10 million?
- What are the loan totals by customer city?
- Which customers do not have recorded loans?
- Which accounts have above-average balances?
- How are accounts ranked by balance across the bank and within each branch?
- What is the chronological transaction number for each account?

## How to Run the Project
1. Download or clone this repository.
2. Open `Banking_Analysis.sql` in MySQL Workbench.
3. Review the SQL script before executing it.
4. Execute the script to create and populate the database.
5. Run the analysis queries and examine the results.

**Important:** The script drops existing tables with matching names in the `banking_practice` database before recreating them. Use a test environment and back up any important data before execution.

## Project Objective
The objective is to strengthen practical SQL skills and demonstrate relational database analysis through banking-related business questions.

## Author
Hariharan S.

## Disclaimer
This is a practice project using sample banking data for educational and portfolio purposes. It is not connected to a real bank.
