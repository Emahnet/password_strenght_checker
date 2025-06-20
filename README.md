🔐 Password Strength Checker

This is a simple Python script that checks the strength of a password based on multiple criteria including length, use of digits, uppercase and lowercase letters, and special characters.

---

📜 Features

- Evaluates passwords based on:
  - Minimum length (more than 8 characters)
  - At least one digit
  - At least one lowercase letter
  - At least one uppercase letter
  - At least one special character
- Outputs password strength as:
  - Very Strong
  - Strong
  - Moderate
  - Weak

---

 🧪 How It Works

The script uses **regular expressions (regex)** to check for:
- Numbers: `\d`
- Lowercase letters: `[a-z]`
- Uppercase letters: `[A-Z]`
- Special characters: `[^A-Za-z0-9]`

Each matched criterion adds to a score that determines overall strength.

---

## ▶️ Usage

 1. Clone the Repository:
```bash
git clone https://github.com/your-username/password-strength-checker.git
cd password-strength-checker
python3 password-strength-checker.py
