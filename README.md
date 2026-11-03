# Bank Withdrawal & Balance Alert System

A Python-based banking application designed to process withdrawal requests, calculate remaining account balances, and provide relevant balance alerts based on predefined banking conditions.

Built as a practical Python project, it demonstrates how fundamental programming concepts can be used to simulate a simple account withdrawal process through a command-line interface.

---

## Overview

The Bank Withdrawal & Balance Alert System is a console-based application that simulates a basic banking withdrawal operation.

The program takes the customer's current account balance and requested withdrawal amount as input. It then calculates the remaining balance and evaluates the transaction against predefined conditions.

Depending on the available balance after withdrawal, the application displays an appropriate message, including insufficient balance notification, zero balance warning, low balance alert, or transaction confirmation.

## Features

- Account balance input
- Withdrawal amount input
- Automatic remaining balance calculation
- Insufficient balance detection
- Zero balance warning
- Low balance alert
- Transaction confirmation message
- Formatted remaining balance with two decimal places
- Conditional transaction handling

---

## Withdrawal Rules

The application follows predefined conditions to determine the outcome of a withdrawal request.

| Condition | System Response |
|---|---|
| Withdrawal amount exceeds account balance | Insufficient Balance |
| Remaining balance is exactly Rs. 0 | Zero Balance Warning |
| Remaining balance is Rs. 1,358 or below | Low Balance Alert |
| Remaining balance is above Rs. 1,358 | Transaction Successful |

### Balance Alerts

**1. Insufficient Balance**

Displayed when the requested withdrawal amount exceeds the available account balance.

**2. Zero Balance Warning**

Displayed when the withdrawal leaves the account balance at exactly Rs. 0.

**3. Low Balance Alert**

Displayed when the remaining account balance is Rs. 1,358 or below, provided the withdrawal is affordable.

**4. Successful Transaction**

Displayed when the withdrawal is completed and the remaining account balance is above Rs. 1,358.

---

## Technologies & Concepts

**Programming Language:** Python 3

**Core Concepts Used:**

- Variables and data types
- User input using `input()`
- Type conversion using `float()`
- Conditional statements (`if`, `elif`, `else`)
- Arithmetic operations
- Comparison operators
- Decision-making and logical flow
- String formatting using `.format()`
- Console output formatting

No external Python libraries are required.

---

## Sample Run

### Customer Input

```text
Enter your account balance (Rs.): 5000
Enter the amount to withdraw (Rs.): 3000
```

### Generated Output

```text
You have withdrawn Rs. 3000.0
Remaining Balance: Rs. 2000.00

========================================
   Transaction Successful. Thank you!
    SEE YOU IN THE NEXT REPOSITORIES..!
========================================
```

### Possible Transaction Outcomes

| Account Balance | Withdrawal | Remaining Balance | Result |
|---:|---:|---:|---|
| Rs. 5,000 | Rs. 6,000 | Not applicable | Insufficient Balance |
| Rs. 5,000 | Rs. 5,000 | Rs. 0 | Zero Balance Warning |
| Rs. 5,000 | Rs. 4,000 | Rs. 1,000 | Low Balance Alert |
| Rs. 5,000 | Rs. 3,000 | Rs. 2,000 | Transaction Successful |

---

## Getting Started

### Requirements

- Python 3
- A code editor or Python-compatible IDE
- No additional package installation required

### Installation & Execution

**1. Clone the repository**

```bash
git clone https://github.com/your-username/BANK-WITHDRAWAL-BALANCE-ALERT-SYSTEM.git
```

**2. Navigate to the project directory**

```bash
cd BANK-WITHDRAWAL-BALANCE-ALERT-SYSTEM
```

**3. Run the Python application**

```bash
python bank_withdrawal_balance_alert.py
```

Follow the on-screen prompts to enter the account balance and desired withdrawal amount.

---

## Project Structure

```text
BANK-WITHDRAWAL-BALANCE-ALERT-SYSTEM/
│
├── bank_withdrawal_balance_alert.py
└── README.md
```

---

## Learning Objectives

This project provides practical experience in applying Python fundamentals to a banking-related scenario.

The main focus is on:

- Understanding conditional decision-making
- Performing balance and withdrawal calculations
- Applying comparison operators
- Handling multiple transaction outcomes
- Implementing nested transaction conditions
- Formatting numerical output for better readability
- Translating simple banking rules into Python logic

---

## Future Improvements

Potential enhancements to the application include:

- Adding input validation for negative balances and withdrawal amounts
- Introducing transaction limits
- Supporting multiple withdrawal transactions
- Maintaining a transaction history
- Adding customer account information
- Generating a detailed withdrawal receipt
- Saving transaction records to a file

---

## Author

**Rammal Ahmed**

AI & Data Science Enthusiast | Microsoft Dynamics 365 CRM Developer | Power Platform | UI/UX Designer | Graphic Designer & Illustrator

[LinkedIn] www.linkedin.com/in/rammal-ahmed-58184b325 · [GitHub] https://github.com/Rammal-Ahmed



I truly value your feedback and welcome any suggestions for improvement

Always open to fresh perspectives, constructive feedback, and new ideas

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Project Status:** Completed
