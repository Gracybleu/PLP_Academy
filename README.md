Welcome to the Fun Calculator! 🎉 This little program lets you add, subtract, multiply, and divide two numbers like an absolute boss! 😎 Whether you're dealing with whole numbers or decimals, this calculator has your back with some simple, clean math.

Features
Supports decimal numbers using float() — because sometimes you need that extra precision! ✨

Performs the four basic math operations:

Addition ➕

Subtraction ➖

Multiplication ✖️

Division ➗

Friendly, step-by-step prompts to guide you through the process.

Outputs neat results with easy-to-understand labels.

How to Use
Run the program.

When prompted, enter the first number (can be decimals).

Enter the second number.

Watch as the calculator computes and displays:

Sum

Difference

Product

Quotient

Important Notes
Please don’t divide by zero! The program assumes you enter valid inputs to avoid any math disasters. 😅

The program reads inputs as floats, so you can enter numbers like 3.14 or -0.5 without a problem.

Example Session
text
Enter the first number: 10.5
Enter the second number: 2
Results of your two numbers:
Sum: 12.5
Difference: 8.5
Product: 21.0
Quotient: 5.25
Code Summary
python
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2

print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")
print(f"Difference: {difference_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")
Have Fun!
This calculator is a great little tool to practice basic arithmetic and Python input/output. Feel free to expand it with extra features like error handling, more operations, or a nicer user interface.

Happy calculating! 🥳💻
