# Banking-System-using-CPP
Sure! Below is a **complete README** file you can copy and paste for your project:

---

# 🏦 Bank Management System in C++

## 📌 Overview

This is a console-based **Bank Management System** developed in C++ that allows users to perform various banking operations like opening an account, depositing and withdrawing funds, checking balance, and closing an account. All account data is persisted using file handling, enabling long-term storage across multiple runs.

---

## 🎯 Features

* ✅ Open a new bank account
* 💰 Deposit and withdraw funds
* 📄 Balance enquiry
* ❌ Close existing accounts
* 📂 View all accounts
* 💾 Data persistence using file I/O
* 🔐 Custom exception handling for insufficient funds
* 🧠 Object-Oriented Programming principles applied

---

## 📁 File Structure

```
.
├── BankSystem.cpp     # Main source code
├── Bank.data          # Auto-generated file to store account data
└── README.md          # Project documentation
```

---

## 🛠️ Technologies Used

* **Language**: C++
* **STL**: `map`, `vector`
* **Concepts**: Classes, File Handling, Exception Handling, Operator Overloading, Static Members

---

## 🚀 How to Run

1. **Clone or Download the Project**

   ```bash
   git clone <your-repo-url>
   cd <project-directory>
   ```

2. **Compile the Code**

   ```bash
   g++ BankSystem.cpp -o BankSystem
   ```

3. **Run the Executable**

   ```bash
   ./BankSystem
   ```

> ✅ Make sure the terminal has write permission to create `Bank.data` file for persistent storage.

---

## 🧑‍💻 Sample Operations

```
***Banking System***

    Select one option below:
    1 Open an Account
    2 Balance Enquiry
    3 Deposit
    4 Withdrawal
    5 Close an Account
    6 Show All Accounts
    7 Quit
Enter your choice:
```

---

## ⚙️ Project Design

* **Account Class**

  * Holds individual account details: name, balance, account number.
  * Provides methods for deposit, withdrawal, and balance access.
  * Uses operator overloading for file read/write.

* **Bank Class**

  * Manages all accounts using `map<long, Account>`.
  * Handles file I/O to read/write all account data.
  * Provides functions for all user operations.

---

## 📌 Minimum Balance Policy

* Each account must maintain a **minimum balance of ₹500**.
* If a withdrawal leads to a balance below this threshold, an `InsufficientFunds` exception is thrown.

---

## 📦 Future Enhancements

* Password protection for accounts
* GUI interface using Qt or another library
* Transaction history for each account
* User login system

---

## 🙋‍♀️ Author

**Srishty Ranjan**
*Beginner in software development, exploring C++ and backend logic.*
Feel free to connect via [LinkedIn](https://linkedin.com) or contribute to enhance the system.

