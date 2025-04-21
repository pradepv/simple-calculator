# simple-calculator
A simple command-line calculator built with Python. Supports basic arithmetic operations including addition, subtraction, multiplication, division, and exponentiation.


# 🔢 Simple Calculator in Python

This is a basic command-line calculator application written in Python. It allows users to perform simple arithmetic operations: addition, subtraction, multiplication, division, and exponentiation.

## 🚀 Features

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)
- Exponentiation (`^`)

## 🧮 How It Works

The program prompts the user to enter two numbers and then choose an arithmetic operation. It calculates and displays the result based on the user's input.

## 📋 Sample Code

```python
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
operation = input("Choose the operation (+, -, *, /, ^): ")

if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    result = num1 / num2
elif operation == '^':
    result = num1 ** num2
else:
    print("Invalid Input")

print(f"The result is {result}")

💡 Example

Enter first number: 10  
Enter second number: 3  
Choose the operation (+, -, *, /, ^): *  
The result is 30.0

🛠 Requirements
Python 3.x

📥 How to Run

Clone the repository:

bash

git clone https://github.com/your-username/simple-python-calculator.git

Navigate to the folder:

bash

cd simple-python-calculator

Run the program:

bash

python calculator.py

📄 License

This project is open source and available under the MIT License.

Feel free to fork this project, improve it, and contribute!

vbnet

Would you like me to generate the license file and `.gitignore` too?












