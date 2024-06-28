# Bank-Account-Management-System

The Python script provides a basic bank account management system allowing users to create accounts, check balance, deposit, withdraw, and update information. Despite limitations, it's a foundational example of object-oriented programming in Python.

# Overview:

This Python script implements a simple bank account management system. Users can create bank accounts, deposit money, withdraw money, check balance, and update account information.

# Classes:

   # Bank Attributes:
   
1.accno: Account number (8 digits).

2.name: Account holder's name.

3.balance: Current balance in the account.

# Methods:
 
1. __init__(self, accNo, name): Constructor method to initialize the bank account with account number, name, and initial balance of 0.

2. Display_information(self): Displays the account information including account number, name, and balance.

3. Check_balance(self): Checks the current balance of the account.

4. Deposit(self): Allows the user to deposit money into the account.

5. Withdraw(self): Allows the user to withdraw money from the account.

6. Change_information(self): Allows the user to change the account holder's name.

7. Banner(self): Displays the menu options.

8. Exit(self): Exits the program.

9. Run(self): Runs the bank account management system by continuously displaying the menu and handling user inputs.

# Usage:

1.Upon running the script, users are prompted to enter their account number and name to create a bank account.

2.The program then displays a menu with options to display account information, withdraw money, deposit money, change account information, or exit the program.

3.Users can choose the desired option by entering the corresponding number.

4.The program continuously runs until the user chooses to exit.
 
 # Limitations:

1.The script does not implement advanced features such as transaction history, authentication, or error handling for invalid inputs.

2.It assumes that the account number is always 8 digits long.
