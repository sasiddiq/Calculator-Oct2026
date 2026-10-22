# Java Calculator – Day 3 Project



### Project Overview

Welcome to the **Java Calculator Project!**


In this hands-on exercise, we build a simple calculator using Java fundamentals. The application accepts two numbers from the user, allows them to select a mathematical operation, and displays the calculated result.

The goal is to understand how Java programming concepts work together to build a functional application.

## Learning Objectives

By completing this project, you will learn:

- Java variables and data types (`int`, `double`)
- Taking user input using the `Scanner` class
- Arithmetic operators (`+`, `-`, `*`, `/`)
- Conditional statements (`if`, `else if`, `else`)
- Comparison operators (`==`, `!=`)
- Handling invalid user choices
- Preventing division-by-zero errors
- Displaying output using `System.out.println()`

## Features

The calculator supports four mathematical operations:

| Option | Operation | Example |
|---|---|---|
| 1 | Addition | 10 + 5 = 15 |
| 2 | Subtraction | 10 - 5 = 5 |
| 3 | Multiplication | 10 × 5 = 50 |
| 4 | Division | 10 ÷ 5 = 2 |

**Additional functionality:**
- Supports decimal numbers
- Validates the selected operation
- Prevents division by zero
- Displays appropriate error messages

## Technologies Used

- **Programming Language:** Java
- **IDE:** Eclipse
- **Java Concepts:** Scanner, Variables, Operators, Conditional Statements
- **Application Type:** Console-Based Application

## Project Structure

```text
JavaFundamentals/
└── src/
    └── day3/
        └── Calculator.java
```

## How to Run the Application

1. Open Eclipse IDE.
2. Create a Java project or open your existing project.
3. Create a package named `day3`.
4. Create a Java class named `Calculator`.
5. Copy the calculator source code into the class.
6. Right-click `Calculator.java`.
7. Select **Run As → Java Application**.
8. Follow the instructions displayed in the console.

## Sample Output

```text
Enter the first number
20
20.0

Enter the second number
10
10.0

Choose an operation
1. Addition
2. Subraction
3. Multiplication
4. Division

1
1
Result: 30.0
```

## Error Handling

### Division by Zero

If the user attempts to divide a number by zero:

```text
Enter the first number
10

Enter the second number
0

Choose an operation
4

Error: Division by zero is not allowed
```

### Invalid Operation

If the user selects an option outside the range of 1–4:

```text
Choose an operation
9

Invalid Choice
```

## Practice Assignments

Once you have successfully executed the calculator, try these challenges:

**Assignment 1 – Add Modulus**

Add a fifth option to calculate the remainder using the `%` operator.

**Assignment 2 – Improve Validation**

Display a user-friendly message when the user enters an invalid operation.

**Assignment 3 – Use Switch Statements**

Replace the `if-else` conditions with a Java `switch` statement.

**Assignment 4 – Test Your Calculator**

Create test cases covering:

- Addition of positive numbers
- Subtraction resulting in a negative number
- Multiplication with zero
- Division with decimal results
- Division by zero
- Invalid operation selection

**Bonus Challenge:** Modify the calculator to allow users to perform multiple calculations without restarting the application.

## Key Takeaways

This project demonstrates how fundamental Java concepts can be combined to create a working application.

More importantly, it introduces the programming logic, input validation, and testing mindset that form the foundation of **QA Automation Engineering**.



**Happy Coding!**

*CloudBerry – Learn. Build. Automate.*
