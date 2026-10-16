# Lab 5: Static Code Analysis — Reflection

## 1. What is static code analysis, and why is it important?

Static code analysis checks source code without executing the program. It helps identify potential bugs, security risks, unused imports, and coding-style problems. It improves code quality and makes programs easier to maintain.

## 2. What is the difference between Pylint, Bandit, and Flake8?

Pylint checks overall code quality, naming conventions, documentation, and possible programming mistakes. Bandit identifies common security risks in Python programs. Flake8 checks code formatting and compliance with Python style guidelines. Using all three provides different perspectives on code quality.

## 3. What issues did you identify and fix in this program?

I fixed several issues, including unsafe SQL query construction, shell command execution, use of MD5 for hashing, unused imports, inconsistent function names, missing docstrings, long lines, and incorrect None comparison. I replaced unsafe SQL construction with parameterized queries and removed unnecessary shell execution.

## 4. How did static analysis improve your program, and what did you learn?

Static analysis helped me identify and correct security, quality, and formatting problems. After making the changes, the Pylint score increased from 2.00/10 to 10.00/10. Bandit reported no issues, and Flake8 reported no errors. I learned that using multiple static analysis tools helps make Python programs safer, cleaner, and easier to maintain.