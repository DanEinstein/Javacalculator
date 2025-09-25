# Simple Java Calculator

## Overview
This is a simple graphical calculator application written in Java using Swing. The calculator supports basic arithmetic operations as well as some scientific functions, including logarithm, trigonometric functions (cosine, sine, tangent), square, square root, cube, cube root, and factorial.

## Features
- Addition, Subtraction, Multiplication
- Logarithm (base 10)
- Trigonometric functions (cos, sin, tan) with input in degrees
- Square, Square Root
- Cube, Cube Root
- Factorial calculation for integers
- Clear inputs and result display

## Requirements
- Java Development Kit (JDK) 8 or later
- A Java IDE or ability to compile and run Java Swing applications

## How to Use
1. Run the `calculator` class.
2. Enter the first number in the "First number" text field.
3. For binary operations (Add, Subtract, Multiply), enter the second number in the "Second number" text field.
4. Click the corresponding operation button.
5. The result will be displayed below the input fields.
6. Use the "Clear" button to reset the inputs and output.

## Notes
- Trigonometric functions expect the input angle in degrees and will convert it to radians internally for computation.
- Factorial operations only accept integer inputs; entering decimals or invalid data will cause an error message.
- Error handling is included for invalid number inputs.

## Code Structure
- The code uses a JFrame as the main window with a red background.
- Inputs are accepted via JTextFields.
- Buttons are arranged using a GridLayout inside a JPanel.
- ActionListeners handle the calculations.
- Calculation results are shown in a JLabel.

## Example
- To calculate \( \sin(30^\circ) \), enter `30` in the first number field and click the "sin" button.
- To add 5 and 10, enter `5` in the first number field, `10` in the second, and click the "Add" button.

## Author
Developed as an example Java Swing calculator application.

## License
This code is provided as-is, free to use and modify.
