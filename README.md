# EXCEPTION-HANDLING-ATM-Banking-System

## Overview
This project is a simple Banking ATM System developed in Python. It demonstrates the use of Object-Oriented Programming (OOP) and Exception Handling to create a reliable application that can handle user errors without crashing.

## Features
- Deposit money into an account.
- Withdraw money from an account.
- Check account balance.
- Prevent negative deposits.
- Prevent invalid withdrawal amounts.
- Handle insufficient account balance using a custom exception.
- Handle invalid user input gracefully.

## Technologies Used
- Python 3
- Object-Oriented Programming (OOP)
- Exception Handling

## Classes
### BankAccount
The BankAccount class provides the following methods:
- deposit() – Adds money to the account.
- withdraw() – Withdraws money from the account.
- check_balance() – Displays the current account balance.

### Custom Exception
- `InsufficientFundsError` – Raised when a withdrawal amount exceeds the available balance.

## Exception Handling
The program handles:
- ValueError
- InsufficientFundsError
- Other unexpected exceptions

This ensures the ATM application continues running even when invalid input is entered.

## How to Run
1. Download or clone this repository.
2. Open the project in your preferred Python IDE (VS Code, PyCharm, etc.).
3. Run the Python file.
4. Follow the on-screen ATM menu.

## Learning Objectives
This project demonstrates:
- Classes and Objects
- Constructors
- Custom Exceptions
- try,except, else, and finally
- Raising exceptions using raise

## Author
Otoo Collins

Electrical and Electronic Engineering Student  
University of Mines and Technology (UMaT)

## Lecturer
Dr. Matthew Cobbinah

## Repository Name
EXCEPTION-HANDLING-ATM-Banking-System
