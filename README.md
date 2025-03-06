# Python-Bank-Account-Management-System

# Project Overview
This project implements a command-line-based Bank Account Management System using Python. It allows users to create accounts, view account details, perform transactions (withdrawals, deposits, and transfers), and view detailed transaction histories. The system includes error handling, validation, and ensures every account has a unique PAN number and account number.

# Features

1. Account Management
Create new accounts with the following details:
PAN Card Number (unique for each account).
Account Holder Name.
Account Type: Savings or Current.
Initial Deposit Amount.
Auto-Generated Account Number (unique 14-digit number).

2. View Account Details
Retrieve and display account information using:
PAN Card Number.
Displayed Information:
Account Holder’s Name
Account Type (Savings/Current)
Account Number
Total Balance

3. Transactions
Users can perform the following transactions:

Deposit: Add money to the account.
Withdraw: Withdraw money from the account (checks for sufficient balance).
Transfer: Send money to another account (recipient identified by their account number).
Transaction details are automatically recorded.

4. Transaction History
View a detailed log of all transactions for an account.
Each record includes:
Date & Time of the transaction.
Transaction Type: Credited, Debited, or Transferred/Received.
Transaction Amount.
Updated Balance after each transaction.

5. Exit Functionality
Safely exits the program when the user chooses to end the session.

