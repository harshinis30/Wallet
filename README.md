



# Wallet - Digital Wallet System  

## Overview  
**Wallet** is a Digital Wallet System implemented in **C++** using **Object-Oriented Programming (OOP)** concepts. The system enables users to manage their wallets, perform transactions, and track financial activities efficiently.  

## Features  
- **User Registration**: Register users with unique IDs and initial balances.  
- **Fund Management**: Add or deduct funds from the wallet.  
- **Fund Transfer**: Secure transactions between users.  
- **Transaction History**: Track past transactions for better financial management.  
- **Account Merging**: Combine two user accounts into one.  
- **Persistent Data Storage**: User details and transactions are stored in files for data persistence.  
- **Error Handling & Validation**: Prevents duplicate usernames, ensures sufficient balance, and validates transaction details.  

## OOP Concepts Used  
- **Encapsulation**: Organizes user and transaction details efficiently.  
- **Inheritance**: Enhances modularity and extends functionalities.  
- **Polymorphism**: Enables flexible handling of different user and transaction types.  
- **Operator Overloading**: Custom operators for fund addition, account merging, and formatted output.  
- **File Handling**: Stores and retrieves user data from text files.  

## Classes & Design  
- **Transaction Class**: Handles transaction details (ID, amount, sender, receiver).  
- **User Class**: Manages user information and wallet operations.  
- **Wallet Class**: Facilitates user registration, fund transfers, and account management.  
- **Base Classes (Abstract Classes)**:  
  - `BaseTransaction` → `Transaction`  
  - `BaseUser` → `User`  
  - `WalletBase` → `Wallet`  

## Installation & Usage  
1. Clone the repository:  
   ```sh
   git clone https://github.com/harshinis30/Wallet.git
   ```
2. Navigate to the project folder:  
   ```sh
   cd Wallet
   ```
3. Compile the program (assuming a C++ compiler like g++):  
   ```sh
   g++ -o wallet main.cpp
   ```
4. Run the program:  
   ```sh
   ./wallet
   ```

 

## License  
This project is licensed under the **MIT License**.  


