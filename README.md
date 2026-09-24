Three-Day Personal Budget Tracker

This repository contains a simple Python program that tracks a user's spending over three days and checks it against a daily budget of $20 and an overall three-day budget of $60. The program is written for an individual assignment focused on fundamental Python concepts, including variables, user input, type conversion, loops, and conditional statements.

The program begins by asking the user to enter their name and initializes a variable named total_spent to zero. It then uses a for loop to repeat three times, once for each day. During each iteration, the program asks the user how much money was spent that day, converts the input to a floating-point number using float(), and adds it to the running total. After each day's entry, an if/else statement checks whether that day's spending was greater than $20 and prints a message accordingly.

Once all three days have been entered, the program prints the total amount spent over the three days and uses a second if/else statement to determine whether the total stayed within the $60 overall budget. If the total is less than or equal to $60, the program reports that the user stayed under budget; otherwise, it reports that the user went over budget.

The program relies only on Python's built-in input(), float(), and print() functions, so no external libraries are required to run it. It follows the constraints of the assignment by avoiding custom functions, classes, file input and output, and data collections such as lists, tuples, dictionaries, or sets.

To run the program, open wk_1_Assigment.ipynb in Jupyter Notebook or Visual Studio Code and run all cells, entering a name and a spending amount for each of the three prompts when asked.

A sample screenshot of the program's output is included in this repository as output.png, showing an example run where the daily and overall budget checks are demonstrated.