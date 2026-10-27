# Password Strength Checker

A beginner-friendly cybersecurity mini project built with Python. It checks a password against five basic rules and displays a strength label with suggestions for improvement.

## Features

- Checks for a minimum length of 8 characters.
- Checks for uppercase letters.
- Checks for lowercase letters.
- Checks for numbers.
- Checks for special characters.
- Displays a score out of 5 and labels the password as **Weak**, **Medium**, or **Strong**.
- Gives suggestions when one or more checks are missing.
- Uses Python's built-in `re` and `getpass` modules; no extra packages are required.

## Requirements

- Python 3
- A code editor such as IDLE, Visual Studio Code, or PyCharm
- A terminal or command prompt that supports `getpass`

## How to Run

1. Save the Python program as `password_checker.py`.
2. Open a terminal or command prompt in the folder containing the file.
3. Run the program:

   ```bash
   python password_checker.py
   ```

   On some systems, use:

   ```bash
   python3 password_checker.py
   ```

4. Enter a made-up test password when prompted.
5. Read the strength score and suggestions.

## Strength Scoring

| Score | Result |
|---:|---|
| 0–2 | Weak |
| 3–4 | Medium |
| 5 | Strong |

The score awards one point for each check passed: length, uppercase, lowercase, number, and special character.

## Example

```text
PASSWORD STRENGTH CHECKER
Enter a password: [input hidden]

Password Strength: STRONG
Score: 5 / 5
Good! Your password meets all five checks.
```

The exact result depends on the test password entered.

## Project Structure

```text
Password-Strength-Checker/
├── password_checker.py
└── README.md
```

## Security and Privacy Note

This is an educational checker, not a complete password-security assessment. A score of **Strong** does not guarantee that a password is secure. Password length, uniqueness, and resistance to guessing also matter.

- Use made-up test passwords for demonstrations.
- Do not store passwords in plain text.
- This program does not need to save or transmit the password.
- Do not enter your real account password into a classroom demo.

## Future Improvements

- Add a graphical interface using Tkinter.
- Create a web version using Flask or Django.
- Add a password generator.
- Add checks for common passwords using a privacy-preserving method.
- Display a visual strength meter.

## License

This project is intended for educational and learning purposes.
