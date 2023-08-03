# ATM_FileHandling

This repository contains a simple ATM (Automated Teller Machine) program implemented in C that uses file handling to store and manage account information.

## Description

The ATM program allows users to perform various banking operations, including creating accounts, reading account information, updating account balances, and deleting accounts. The account information is stored in a file named `account.dat`.

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/your-username/ATM_FileHandling.git
   ```

2. Compile the source code:

   ```
   gcc atm.c -o atm
   ```

3. Run the program:

   ```
   ./atm
   ```

4. Follow the on-screen instructions to log in, create accounts, and perform banking operations.

## Features

- **Login System**: Users need to enter an account number and a PIN to log in. The program reads account information from `account.dat` to authenticate users.

- **Create Account**: Users can create new accounts by providing an account number, PIN, initial balance, and date.

- **Read Account Information**: Users can view account information based on various choices, such as account number, PIN, balance, date, or all accounts in `account.dat`.

- **Deposit and Withdraw**: Users can deposit or withdraw funds from their accounts. The account balance is updated accordingly.

- **Delete Account**: Users can delete a specific account or all accounts stored in `account.dat`.

## File Structure

- `atm.c`: The C source code for the ATM program.
- `account.dat`: The data file to store account information.

## Notes

- This is a simple demonstration of an ATM system and is not intended for real-world use. It does not use encryption or robust security measures.

- The program uses file handling to read and write account information, but in a real-world scenario, a proper database would be more appropriate for managing customer data.

- This code is provided as-is, without any warranties or support. Use it at your own risk.

## Contributions

Contributions to this repository are welcome. If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

---
Please note that the actual content may need to be adapted or expanded based on the specific features and complexity of the program. Also, don't forget to replace "your-username" in the clone URL with your GitHub username.
