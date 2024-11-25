# Expense Tracker
## Overview
The Expense Tracker is a Python program that allows users to manage and analyze their expenses. It supports adding, reporting, saving, and loading expense data using a pandas DataFrame for data manipulation.

## Features
### Add Expenses: Record expenses with details such as date, category, amount, and description.
### Generate Reports:
Total spending.
Spending breakdown by category.
Spending breakdown by month.
### Save Data: Save expenses to a CSV file for future reference.
### Load Data: Load previously saved expenses from a CSV file.

## Code Structure
### Class: ExpenseTracker

#### Attributes:
self.expenses: A pandas DataFrame to store expense details.
#### Methods:
add_expense(amount, category, description): Adds a new expense with the current date.

generate_report(): Calculates and displays total spending, spending by category, and spending by month.

save_data(file_name): Exports expense data to a CSV file.

load_data(file_name): Imports expense data from a CSV file.
