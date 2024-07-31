# Customer-Financial-Data-Analysis
The "Customer Financial Data Analysis" project aims to clean, integrate, and analyze customer financial data from multiple sources, including bank deposits, saving accounts, loans, and transaction records. The project involves the following key tasks:

Data Cleaning:

Removal of duplicates and handling of missing values in the Accounts and Loan worksheets.
Cleaning of the Bank Deposit and Saving Accounts columns by removing extraneous characters and converting them to numeric formats for accurate analysis.
Data Integration:

Duplication and renaming of the Customer worksheet to create a consolidated view named "All_customer_details."
Merging data from the Accounts, Loan, and Transaction worksheets into the "All_customer_details" sheet using VLOOKUP-like operations to include account types, opening balances, loan details, and transaction histories.
Balance Calculation:

Calculation of the balance for each customer by finding the difference between Current_deposit (Bank Deposit) and Saving_deposit (Saving Accounts).
Identification of customers eligible for rewards based on their current account balances, specifically those with balances exceeding #500,000, and rewarding them with a 2% addition to their balance.
Data Visualization:

Creation of visual charts to represent key financial metrics, providing insights into customer financial behavior and account statuses.
