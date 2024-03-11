# Customer Banking

Module 3 Challenge

This project implements a customer banking system that allows users to calculate and track interest earned on savings and CD accounts. Users can enter their savings and CD account information, view the interest earned, and see the updated balances after a specified number of months.

# Import the Account class from the Account.py file
from Account import Account
Function: create_savings_account
The create_savings_account function creates a savings account, calculates interest earned, and updates the account balance.

Parameters:
balance (float): The initial savings account balance.
interest_rate (float): The APR interest rate for the savings account.
months (int): The length of months to determine the amount of interest.
Returns:
float: The updated savings account balance after adding the interest earned.
float: The interest earned.
Usage:
To use the create_savings_account function, follow these steps:

Call the function with the appropriate parameters.
The function will return the updated savings account balance and the interest earned.
Example:
balance = 1000.0
interest_rate = 5.0
months = 12

# Import the Account class from the Account.py file
from Account import Account
Function: create_cd_account
The create_cd_account function creates a CD account, calculates interest earned, and updates the account balance.

Parameters:
balance (float): The initial CD account balance.
interest_rate (float): The APR interest rate for the CD account.
months (int): The length of months for the CD.
Returns:
float: The updated CD account balance after adding the interest earned.
float: The interest earned.
Usage:
To use the create_cd_account function, follow these steps:

Call the function with the appropriate parameters.
The function will return the updated CD account balance and the interest earned.
Example:
balance = 1000.0
interest_rate = 5.0
months = 12
