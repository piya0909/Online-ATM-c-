# ATM Simulator in C++

A simple command-line ATM simulation system written in C++ that mimics basic banking operations like checking balance, withdrawing money, updating passwords, and viewing a mini statement. Perfect for beginners looking to understand basic control structures, loops, and string handling in C++.

---

## Features

### Login Authentication
- Users must enter the correct password to access any features.
- The default password is set to `"0000"` for demonstration purposes.

### Menu-Driven Interface
- Intuitive and user-friendly menu that guides users through various ATM functionalities.

### Balance Inquiry
- Allows the user to check their current account balance.

### Withdraw Money
- Prompts the user to enter an amount.
- Checks for sufficient balance before processing the withdrawal.
- Updates the remaining balance accordingly.

### Mini Statement
- Displays:
  - Account holder name (dynamically entered at runtime)
  - Current balance
  - Last transaction date (currently static for demo purposes)

### Change Password
- Lets the user reset the ATM password.
- New password replaces the old one and is active in-session.

### Exit Option
- Gracefully terminates the session when the user selects "5. Exit".

### Session Loop
- Users can continue making transactions until they choose to exit.
- Eliminates the need to restart the program for multiple actions.

---

## Requirements

- C++ compiler (e.g., g++, clang)
- Basic understanding of input/output, conditionals, and loops

---

## Learning Concepts

This project covers:
- `std::string` operations
- Conditional statements (`if`, `switch`)
- Looping (`do-while`)
- Input/output using `cin` and `cout`
- Code structure and modular thinking

---

## Future Enhancements (Optional Ideas)
- Multiple account support with username-password validation
- File handling to save transaction history
- Dynamic transaction logs
- Improved password protection (e.g., masking input)
