# 🏦 ATM System
This is a simple Console-Based ATM System developed in Python.
It allows users to log in, check their balance, deposit money, withdraw funds, and view transaction history — all through an easy-to-use text menu.

## ✨ Features
User Authentication
Login using a valid username and password from the predefined users list.

## Check Bank Balance
View your current available balance at any time.

## Deposit Money
Deposit any amount to your account, instantly updating your balance and transaction history.

## Withdraw Money
Withdraw funds from your account (only if sufficient balance is available).

## View Transaction History
View a detailed history of all your deposits and withdrawals made during the session.

## Exit the System
Safely exit the ATM system anytime.

## 📋 How It Works
At the start, users are prompted to login with their credentials.
- If login is successful, a menu appears with different banking operations.
- Bank balance is initially set to Rs 1000.
- All successful transactions are stored and displayed in the transaction history.

## 🚀 Getting Started
To run the program:
- Make sure Python is installed.
- Copy the code into a .py file.
- Run the file using any Python IDE or through command line:

## 🔑 Default User Credentials
Username	Password
urooj	124
zainab	12345
(You can add more users by updating the users dictionary.)

## 📸 Sample Interface
```
----------------------------------
Welcome to ATM System
----------------------------------
Enter your username: urooj
Enter your password: 124
----------------------------------
Login Successful!!!
----------------------------------

1. Check your Bank Balance.
2. Deposit Money.
3. Withdraw Money.
4. View Transaction History.
5. Exit.
Select an option:
```

## 📌 Notes
- Invalid inputs are handled gracefully with error messages.
- Balance updates instantly after every deposit and withdrawal.
- Transaction history is shown only for the current session (not saved after exit).

## 🛠 Built With
- Python (Core Language Features)
- Lambda Functions for balance operations
- Lists for Transaction Tracking
- Simple Console UI for easy navigation








