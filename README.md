# Password Strength Checker

## Overview

This project is a simple Python program designed to evaluate the strength of passwords. 
It checks passwords against a set of criteria to determine their robustness, providing users with feedback to improve their password security.

## Features

- Checks the length of the password.
- Ensures the presence of both uppercase and lowercase letters.
- Verifies the inclusion of digits.
- Confirms the use of special characters.
- Provides a strength score and suggestions for improvement.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
   bash
   git clone https://github.com/TechAngell/password-strength-checker.git
   cd password-strength-checker
   

2. (Optional) Create and activate a virtual environment:
   bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   

3. Install any dependencies (if needed):
   bash
   pip install -r requirements.txt
   

## Usage

To run the password strength checker, execute the following command:
bash
python password_strength_checker.py


### Example Usage

After running the script, you will be prompted to enter a password. The program will then evaluate the password and provide feedback.

bash
Enter a password: P@ssw0rd123

Strength: strong
Suggestions: 
- your password is extremely strong!



## Password Strength Criteria

1. *Length*: Minimum length of 8 characters.
2. *Uppercase Letters*: At least one uppercase letter (A-Z).
3. *Lowercase Letters*: At least one lowercase letter (a-z).
4. *Digits*: At least one digit (0-9).
5. *Special Characters*: At least one special character (e.g., !, @, #, $, etc.).





