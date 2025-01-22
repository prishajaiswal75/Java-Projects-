# Java-Projects-Calculator Program
About the Program
This program helps you do various calculations easily using a menu. You can add, subtract, multiply, divide, find the Fibonacci sequence, and calculate the mean and variance of numbers. It has three main parts:

Main.java - The main program where everything starts.
UserInput.java - A helper to take input from you.
Calculator.java - A set of tools to do all the math.
How It Works
The program will show you a menu with different options.
You pick an option (like Add, Subtract, etc.).
It asks for numbers or other inputs.
It calculates the result and shows it.
You can keep using it or exit the program.
What Each File Does
Main.java
This is the starting point of the program. It shows the menu, takes your choice, and calls the correct function.

Functions in Main.java:
main(String[] args):
Runs the program.
Shows the menu and asks you to pick an option.
Calls the correct calculation based on your choice.
UserInput.java
This file is like a helper. It asks for your input and collects the numbers.

Functions in UserInput.java:
getNumberInput(String prompt):

Shows a message (prompt) asking for a number.
Lets you type a number and gives it back to the program.
getArrayInput():

Asks how many numbers you want in a list.
Lets you type the numbers one by one.
Gives the list of numbers back to the program.
Calculator.java
This is where all the math happens. It has many tools to do calculations.

Functions in Calculator.java:
add(double a, double b):

Adds two numbers and gives the result.
subtract(double a, double b):

Subtracts the second number from the first one.
multiply(double a, double b):

Multiplies two numbers and gives the result.
divide(double a, double b):

Divides the first number by the second one.
Note: It won’t divide if the second number is 0 (to avoid errors).
printFibonacci(int n):

Shows the first n numbers of the Fibonacci sequence.
The Fibonacci sequence starts with 0 and 1, and each number is the sum of the two before it.
calculateMean(double[] array):

Finds the average of a list of numbers.
calculateVariance(double[] array):

Measures how spread out the numbers are from the average (mean).
