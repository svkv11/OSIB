# Password Generator

**Author:** VENKAT KALYAN VARMA SANGARAJU

---

## Overview

A Python-based Password Generator that creates strong, randomized passwords based on user-defined preferences. Users can customize the length and choose which character types to include — uppercase letters, lowercase letters, digits, and special symbols.

---

## Features

- Generate passwords of any desired length
- Toggle inclusion of:
  - Uppercase letters (A–Z)
  - Lowercase letters (a–z)
  - Digits (0–9)
  - Special characters (!@#$%^&* etc.)
- Ensures randomness using Python's `random` or `secrets` module
- Simple command-line interface

---

## How to Run

```bash
python password_generator.py
```

---

## Sample Usage

```
Enter desired password length: 12
Include uppercase letters? (yes/no): yes
Include digits? (yes/no): yes
Include special characters? (yes/no): yes

Generated Password: G7$kPw#2Lm@9
```

---

## Requirements

- Python 3.x
- No external libraries required (uses built-in `random`, `string`, or `secrets`)

---

## Security Note

For generating passwords used in real applications or secure storage, it is recommended to use Python's `secrets` module instead of `random`, as `secrets` is designed for cryptographic use.

```python
import secrets
```

---

## Future Improvements

- Option to generate multiple passwords at once
- Password strength indicator
- Copy generated password to clipboard using `pyperclip`
- Save generated passwords to an encrypted file

---

*Created by VENKAT KALYAN VARMA SANGARAJU*
