# 🏦 Secure Bank Management System

A C++ console application that simulates core banking functionalities with an emphasis on security and user authentication.

## 🔒 Security Features
- **PIN Verification**: Every transaction (Deposit, Withdrawal, Info Display) requires a correct 4-digit PIN.
- **Private Data Members**: User balance and security codes are hidden from direct access, maintaining system integrity.

## 🚀 Main Operations
- **Account Creation**: Set up your profile and security PIN.
- **Secure Deposits**: Add funds to your balance after authentication.
- **Safe Withdrawals**: Prevents overdrawing and verifies user identity before releasing funds.
- **Balance Inquiry**: View account details and current standing securely.

## 🛠️ Tech Stack
- **Language**: C++
- **Security Logic**: Private member functions for internal verification.
- **Currency**: EGP (Egyptian Pounds).

## 💻 How to Run
1. Open your terminal/compiler.
2. Clone the repository.
3. Compile the source code:
   ```bash
   g++ BankAccount.cpp -o bank_system
