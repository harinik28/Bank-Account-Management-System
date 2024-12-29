# **Bank Account Management System**

A comprehensive C# project simulating a **bank account management system** with various account types and functionalities. This project demonstrates object-oriented programming concepts like inheritance, encapsulation, and constructor chaining.

## **Features**
- **Base Bank Account Class**:
  - Manage deposits and withdrawals.
  - Track transaction history with timestamps and notes.
  - Enforce a **minimum balance** using constructor chaining.
  
- **Derived Account Types**:
  - **Interest Earning Account**:
    - Automatically apply monthly interest if balance exceeds a threshold.
  - **Line of Credit Account**:
    - Support overdraft with interest charges applied for negative balances.
  - **Gift Card Account**:
    - Add optional monthly deposits for recurring credits.

## **Technical Highlights**
- **Constructor Chaining**:
  - A secondary constructor for the base `BankAccount` class to support optional minimum balance.
- **Encapsulation**:
  - Use of private fields and public properties for data management.
- **Polymorphism**:
  - Overridden methods for performing month-end transactions specific to each account type.
- **Transaction Logging**:
  - Detailed transaction history with balance updates.

## **Project Structure**
- `BankAccount.cs`: The base class for managing general account operations.
- `Transaction.cs`: A helper class to log transaction details.
- `InterestEarningAccount.cs`: A derived class implementing interest-earning functionality.
- `LineOfCreditAccount.cs`: A derived class with overdraft support.
- `GiftCardAccount.cs`: A derived class supporting monthly deposits.
- `Program.cs`: A demo program showcasing account operations and inheritance.

## **Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/harinik28/Bank-Account-Management-System
