<img width="470" alt="image" src="https://github.com/user-attachments/assets/30f6059b-1960-42c7-8238-012b71d9c74e" />

# Simple Calculator Web App
This is a basic calculator web application written in JavaScript that supports basic arithmetic operations: addition, subtraction, multiplication, and division. The app is designed to provide an intuitive and interactive interface for performing calculations.

# Features
Basic arithmetic operations: The calculator supports addition, subtraction, multiplication, and division.
Clear functionality: The calculator allows users to reset the input and start fresh.
Interactive interface: Users can click on the number and operator buttons to perform calculations.
Error handling: It handles division by zero by displaying "Error".
# Project Structure
The project consists of the following components:

HTML: Provides the structure of the calculator (divs for numbers, operators, input display, and result).
CSS: (Optional) Styles to format the calculator's appearance.
JavaScript: Contains the logic for handling user input, performing calculations, and updating the display.
# Installation
Clone the repository:
# bash

git clone https://github.com/yourusername/calculator.git
Navigate to the project directory:
bash

cd calculator
Open index.html in your preferred browser.
How It Works
Numbers and Operators:

Users click on the number or operator buttons to input values and operators.
The number and operator values are appended to the input field (#input).
Calculate:

When the "equals" button (#result) is clicked, the calculate() function is called to evaluate the expression based on the selected operator.
The result is displayed in the input field, and the first number is updated for potential future calculations.
Clear:

The clear button resets the calculator’s state by clearing the input field and resetting all variables.
Error Handling:

In case of division by zero, the calculator displays "Error".
Code Breakdown
Variables:

number1 and number2: Store the two numbers to be operated on.
operator: Stores the current arithmetic operator.
isOperatorSet: A flag to check whether the operator has been selected.
Event Listeners:

Numbers and operators are clickable, updating the input field when clicked.
The result button performs the calculation when clicked.
The clear button resets the calculator state.
Calculation:

Based on the selected operator, the calculator performs the corresponding arithmetic operation.
# Example Usage
Click on numbers and operators to form an expression (e.g., "3 + 5").
Press the "=" button to see the result.
Press the "C" button to clear the calculator.


# Contributing
If you’d like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome!
