# Bank-Account-Management-System
The Python script provides a basic bank account management system allowing users to create accounts, check balance, deposit, withdraw, and update information. Despite limitations, it's a foundational example of object-oriented programming in Python.

Overview:

This Python script implements a simple bank account management system. Users can create
bank accounts, deposit money, withdraw money, check balance, and update account information.
Classes:

Bank:

 Attributes:

o accno: Account number (8 digits)
o name: Account holder's name
o balance: Current balance in the account

 Methods:
 
o __init__(self, accNo, name): Constructor method to initialize the bank
account with account number, name, and initial balance of 0.
o display_information(self): Displays the account information including
account number, name, and balance.

o check_balance(self): Checks the current balance of the account.
o deposit(self): Allows the user to deposit money into the account.
o withdraw(self): Allows the user to withdraw money from the account.
o change_information(self): Allows the user to change the account holder's
name.
o banner(self): Displays the menu options.
o exit(self): Exits the program.
o run(self): Runs the bank account management system by continuously
displaying the menu and handling user inputs.
Usage:

 Upon running the script, users are prompted to enter their account number and name to
create a bank account.
 The program then displays a menu with options to display account information, withdraw
money, deposit money, change account information, or exit the program.
 Users can choose the desired option by entering the corresponding number.
 The program continuously runs until the user chooses to exit.
Limitations:
 The script does not implement advanced features such as transaction history,
authentication, or error handling for invalid inputs.
 It assumes that the account number is always 8 digits long.
