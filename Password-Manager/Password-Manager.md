# Password Manager

A simple password manager written in Python using the `cryptography` library.  
It allows you to save and view encrypted passwords from the command line.

## Features
- Creates a secure encryption key on first run (`key.key` file).
- Stores account names and encrypted passwords in `passwords.txt`.
- Add new accounts with passwords.
- View existing accounts with decrypted passwords.

## How to Use
1. Install the required package:
   ```bash
   pip install cryptography
2. Run the program:
   ```bash
   main.py
3. Choose an option:

   add → Add a new password <br>
   view → View saved passwords <br>
   q → Quit the program.
