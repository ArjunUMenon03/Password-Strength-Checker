# Password Strength Checker

This Python script evaluates the strength of a given password based on common password security criteria. It helps users determine how secure their password is by checking for length, uppercase and lowercase letters, digits, and special characters.

---

## Features

- Checks if the password length is at least 8 characters.
- Verifies the presence of uppercase letters.
- Verifies the presence of lowercase letters.
- Checks for digits in the password.
- Checks for special characters (e.g., `!@#$%^&*(),.?":{}|<>`).
- Classifies password strength into categories: Very Weak, Weak, Medium, Strong, Very Strong.
- Provides detailed feedback on which criteria have been met.

---

## Requirements

- Python 3.x

No external libraries are required as it uses Python's built-in `re` module.

---

## How It Works

The script uses regular expressions to check for:

- Uppercase letters `[A-Z]`
- Lowercase letters `[a-z]`
- Digits `[0-9]`
- Special characters from a predefined set

It counts how many of these conditions the password meets and assigns a strength category accordingly.

---

## Usage

1. Save the script as `password_strength_checker.py`.
2. Run the script using Python:

python password_strength_checker.py


3. Enter the password when prompted.
4. The script will display the strength rating along with which criteria were met or not.

---

## Example

Enter a password to check its strength: P@ssw0rd123
Password Strength: Very Strong
Criteria met:
Length >= 8: ✔
Contains uppercase letter: ✔
Contains lowercase letter: ✔
Contains digit: ✔
Contains special character: ✔

---

## Author

Arjun U Menon

---

## License

This project is provided for educational purposes.
