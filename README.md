# BankApp

A console-based banking application built with **Core Java** using **Object-Oriented Programming (OOP)** concepts. It lets a user log in with a PIN and perform basic banking operations from the command line.

## Features

- PIN-based login
- Check account balance
- Deposit money
- Withdraw money
- Display account details
- Menu-driven interface that runs until the user chooses to exit

## Concepts Used

- **Classes and objects:** a `BankAccount` class models the account, and `BankApplication` runs the program
- **Encapsulation:** account number, holder name, PIN and balance are `private` and accessed only through methods
- **Constructor:** initializes the account details
- **Control flow:** `do-while` loop, `switch` statement and `if-else` conditions
- **Input handling:** `Scanner` for reading user input from the console

## Input Validation

- Deposit amount must be greater than zero
- Withdrawal amount must be greater than zero
- Withdrawal is rejected if the amount is more than the available balance ("Insufficient Balance")
- An incorrect PIN is rejected ("Invalid PIN")
- An invalid menu choice shows an "Invalid Choice" message

## How to Run

1. Make sure the **JDK** is installed.
2. Clone the repository:
   ```
   git clone https://github.com/Mahananda-Nova/BankApp.git
   cd BankApp
   ```
3. Compile and run:
   ```
   javac BankApplication.java
   java BankApplication
   ```

## Demo Account

The program starts with a sample account for testing:

| Field          | Value |
|----------------|-------|
| Account Number | 1001  |
| Account Holder | Rahul |
| PIN            | 1234  |
| Balance        | 5000.0 |

## Sample Output

```
Welcome to Bank Application
Enter PIN:
1234
Login Successful

1. Check Balance
2. Deposit Amount
3. Withdraw Amount
4. Display Account Details
5. Exit
Enter your choice:
2
Enter deposit amount:
1000
Amount Deposited Successfully
Updated Balance: 6000.0
```

## Future Improvements

- Support multiple accounts
- Store data in a database (MySQL) using JDBC
- Add transaction history
- Limit the number of wrong PIN attempts

## Author

**Mahananda Biradar**
GitHub: [Mahananda-Nova](https://github.com/Mahananda-Nova)
