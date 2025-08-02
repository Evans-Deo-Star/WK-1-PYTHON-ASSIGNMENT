# 🧮 Basic Calculator in Python

This is a simple command-line calculator built using Python. It supports basic arithmetic operations like addition, subtraction, multiplication, and division.

## 🚀 Features

- Add (`+`)
- Subtract (`-`)
- Multiply (`*`)
- Divide (`/`) — with error handling for division by zero

## 📝 How It Works

The calculator prompts the user to:

1. Enter the first number
2. Choose an operator (`+`, `-`, `*`, `/`)
3. Enter the second number

Based on the input, it calculates and displays the result. If an invalid operator is entered or division by zero is attempted, it handles the error gracefully.

## 💻 Example Usage

Enter first number: 10
Enter operator (+, -, *, /): *
Enter second number: 5
Result: 50.0

## 🧠 Code Overview

python
num1 = float(input("Enter first number: "))
operator = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if operator == '+':
    result = num1 + num2
elif operator == '-':
    result = num1 - num2
elif operator == '*':
    result = num1 * num2
elif operator == '/':
    if num2 != 0:
        result = num1 / num2
    else:
        result = "Error: Division by zero"
else:
    result = "Invalid operator"

print("Result:", result)

▶️ How to Run
Save the code to a file (e.g., calculator.py), then run it using:
python calculator.py
