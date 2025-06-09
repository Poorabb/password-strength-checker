# 🔐 Password Strength Checker - Python CLI Tool

This is a simple Python-based password strength checker that analyzes user-input passwords for common security rules like length, uppercase letters, digits, and special characters.

---

## ✨ Features

- 🚫 Rejects passwords with spaces  
- 📏 Requires minimum length of 8 characters  
- 🔡 Checks for at least one uppercase letter  
- 🔢 Checks for at least one numeric digit  
- 💥 Checks for at least one special character  
- 🔁 Prompts user repeatedly until a strong password is entered  

---

## 📦 Requirements

- Python 3.6+  

No external libraries needed — uses only Python's built-in modules.

---

## 🚀 How to Run

```bash
$ python password_checker.py
 PASSWORD CHECKER 🧑🏻‍💻 


Enter new password: password
Very weak password! Use atleast 8 characters

Enter new password: password123
weak password! Include atleast 1 uppercase.

Enter new password: Password123
Average password! Include atleast 1 special character.

Enter new password: Password123!
Password SET !
