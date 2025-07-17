# Fun Calculator 🎉

A simple and fun calculator that performs basic arithmetic operations (addition, subtraction, multiplication, and division) on two user-input numbers. 

## Features ✨
- Takes two numbers as input (supports decimals! 🧮)
- Performs the following operations:
  - **Addition** (`num1 + num2`) ➕
  - **Subtraction** (`num1 - num2`) ➖
  - **Multiplication** (`num1 * num2`) ✖️
  - **Division** (`num1 / num2`) ➗ (Note: Division by zero will crash the program! 🚨)
- Prints the results in a fun and readable format. 🎉

## How to Use 🚀
1. Run the script in a Python environment (Python 3.x recommended).
2. Enter the first number when prompted.
3. Enter the second number when prompted.
4. The calculator will display the results of all four operations.

### Example Input/Output:
```
Enter the first number: 10
Enter the second number: 2
Results of your two numbers:
Sum: 12.0
Difference: 8.0
Product: 20.0
Quotient: 5.0
```

## Notes ⚠️
- The calculator does not handle division by zero gracefully—if `num2` is `0`, the program will crash with an error. For a more robust version, consider adding error handling (e.g., `try-except`).
- The code uses `float()` for input, so both integers and decimals are supported.

## Future Improvements 🔧
- Add error handling for invalid inputs (e.g., non-numeric values).
- Extend functionality to support more operations (e.g., exponentiation, modulus).
- Add a loop to allow multiple calculations without restarting the program.

---

Enjoy calculating like a boss! 😎
