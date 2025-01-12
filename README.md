# Calculator Program in Python

This is a simple Python-based calculator program that provides basic arithmetic operations. The program runs in the terminal, allowing the user to perform multiple calculations interactively.

## Features

The calculator supports the following operations:

1. Addition
2. Subtraction
3. Multiplication
4. Division (with error handling for division by zero)
5. Modulus (remainder of division)
6. Exponentiation

## How It Works

1. The user selects an operation by entering a number (1–6) corresponding to the desired calculation.
2. The user is prompted to input two numbers.
3. The calculator performs the operation and displays the result.
4. The user can choose to perform another calculation or exit the program.

## How to Run

1. Ensure you have Python installed on your system (version 3.x is recommended).
2. Download or clone the repository containing this program.
3. Run the program using the following command:
   ```bash
   python calculator.py
   ```
4. Follow the on-screen instructions to use the calculator.

## Error Handling

- The program validates user input to ensure only numeric values are processed.
- Division by zero is handled gracefully with an appropriate error message.

## Example Output

```
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Modulus
6. Exponent

Enter choice (1/2/3/4/5/6): 1
Enter first number: 5
Enter second number: 3
5.0 + 3.0 = 8.0

Do you want to perform another calculation? (y/n): y
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Modulus
6. Exponent

Enter choice (1/2/3/4/5/6): 4
Enter first number: 10
Enter second number: 0
Error! Division by zero.

Do you want to perform another calculation? (y/n): n
Exiting the calculator. Goodbye!
```

## Contributing

Contributions are welcome! If you have suggestions for new features or improvements, please submit a pull request or open an issue.

## License


## Acknowledgments

- Developed with Python for learning and demonstration purposes.

