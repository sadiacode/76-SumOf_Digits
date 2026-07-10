# Sum of Digits
## Description
This project is a Python program that demonstrates the use of while loop in Python. A while loop repeatedly executes a block of code as long as **a specified condition is True**. It is useful when the number of iterations is not fixed or depends on a condition.
## Syntax
```python
while condition:
   # Code to execute if condition is True
```
## Concepts Used
- Variables
- while Loop
- Comparison Operators
- Increment and Decrement
- Modulus Operator(%)
- Floor Division(//)
## Technologies Used
- Pycharm
- Python 3
## Working of the Code
1. The program asks the user to input a number in the variable 'num'.
2. The variable 'sum' is initialized with '0'.
3. The 'while' loop runs as long as number is greater than '0'.
4. The statement 'digit = num % 10' extracts the last digit of the number.
5. The statement 'sum += digit' adds the extracted digit to the running total.
6. The statement 'num //= 10' removes the last digit from the number.
7. The loop continues until the condition becomes false.
8. Finally, the program displays the sum of all digits.

## How to run
1. Clone the repository.
2. Open the project in pycharm.
3. Run the 'main.py' file.
4. View the result.
## Sample Output
```text
Enter a number: 12345

Sum of digits is: 15
```
## Author
- Sadia
- Github: [sadiacode](https://github.com/sadiacode)
