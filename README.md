# Python Assignment 3 - Loops and Functions

This repository contains solutions for Python Assignment 3, focusing on iteration, control statements, and user-defined functions.

## 📋 Assignment Overview

**Objective:** To develop an understanding of:
- Iteration using `while` loop and `for` loop
- Control statements: `break`, `continue`, `pass`, and `else`
- Function creation and usage
- Logical problem-solving using real-world examples

## 🗂️ Tasks Included

### Task 1: While Loop & Control Statements - Number Guessing Game
A interactive game where the user has to guess a random number between 1 and 10.

**Concepts Used:**
- `random.randint()` for secret number generation
- `while` loop with `attempts = 3`
- `continue` to skip invalid/out-of-range guesses
- `break` to exit when guess is correct
- `while-else` to display "Better luck next time!" if attempts run out

**How to Run:**
```python

### Task 2: For Loop - Multiplication Table Generator
Generates multiplication table (1 to 10) for a user-given number.
Concepts Used:
for loop with range(1, 11)
User input and formatted output

### Task 3: Function - BMI Calculator
Calculates Body Mass Index using a user-defined function.
Formula: BMI = weight (kg) / [height (m)]²

Concepts Used:
User Defined Function Type 4: With Arguments and With Return Value
def calculate_bmi(weight, height):
Return value and float formatting :.2f

🚀 Technologies Used
Python 3.x
Google Colab / Jupyter Notebook
Modules: random

▶️ How to Run This Project
Clone the repository:

📁 Deliverables
Assignment_3_Loops_and_Functions.ipynb - Complete notebook with all 3 tasks
README.md - Project documentation
import random
secret_number = random.randint(1, 10)
# ... (full code in notebook)
