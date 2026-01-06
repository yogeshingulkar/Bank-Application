# 🏦 Bank Application (Java Console Project)

A **menu-driven Java console banking application** that simulates basic banking operations such as account creation, login, deposit, withdrawal, balance checking, and account information display.

This project is built using **Core Java fundamentals** and demonstrates logical thinking, control flow, and user interaction via the console.

---

## 📌 Project Overview

The Bank Application allows a user to:
- Create a bank account
- Login using phone number and PIN
- Deposit money
- Withdraw money securely using PIN validation
- Check account balance
- View account details
- Logout safely

The application runs continuously until the user chooses to exit.

---

## 🛠 Technologies & Concepts Used

- **Language:** Java  
- **Core Java Concepts:**
  - Classes & static members
  - Loops (`for(;;)`)
  - Conditional statements
  - `switch-case`
  - User input using `Scanner`
  - Authentication logic
- **Application Type:** Console-based
- **Build:** Executable JAR

---

## 📂 Project Structure

Bank-Application/
│
├── Bank.java // Source code
├── Bank.jar // Executable JAR file
└── README.md // Documentation

yaml
Copy code

---

## ▶️ How to Run the Application

### Option 1: Run using JAR file
Ensure Java is installed on your system.

```bash
java -jar Bank.jar
Option 2: Run using source code
bash
Copy code
javac Bank.java
java Bank
🔐 Application Flow
1. Welcome Menu
Existing User

Create Account

2. Create Account
Enter Name

Enter Contact Number

Set PIN

Initial Deposit

3. Login
Phone Number

PIN Verification

4. Home Menu
Deposit Amount

Withdraw Amount

Check Balance

Account Information

Logout

🧠 Key Learnings from This Project
How static variables maintain application-wide state

Authentication using user input

Menu-driven program design

Logical validation for transactions

Continuous execution using infinite loops

Practical use of Scanner for console input

⚠️ Current Limitations
Supports only single user

No data persistence (data resets when program stops)

No exception handling for invalid inputs

Console-based (no GUI)

🚀 Possible Enhancements
Multiple user account support

File or database-based storage

Exception handling

Transaction history

Password masking

GUI using JavaFX or Swing

Object-Oriented redesign (non-static approach)

👨‍💻 Author
Yogesh Ingulkar
Aspiring Software Developer | Java Enthusiast
