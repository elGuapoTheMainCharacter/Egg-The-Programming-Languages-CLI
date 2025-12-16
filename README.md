# Egg-The-Programming-Languages-CLI
A simple programming language I built that uses prefix notation.
Egg Programming Language

Egg is a simple programming language implemented in JavaScript. It supports basic arithmetic operations, conditional statements, loops, and functions.

Getting Started
To use Egg, simply call the `run` function with a string containing your Egg code.

Examples
- Print "Hello, World!":
run(`print("Hello, World!")`);
- Add two numbers:
run(`print(+(2, 3))`);
- Define a variable:
run(`define(x, 5)`);
run(`print(x)`);
- Use an if statement:
run(`if(true, print("True"), print("False"))`);
- Use a while loop:
run(`do(define(count, 0), while(<(count, 5), do(print(count), define(count, +(count, 1))))))`);
- Define and call a function:
run(`define(add, (a, b) => +(a, b))`);
run(`print(add(2, 3))`);
Special Forms
Egg supports the following special forms:

- `if`: Conditional statement
- `while`: Loop
- `do`: Evaluate multiple expressions
- `define`: Define a variable or function

Operators
Egg supports the following operators:

- `+`: Addition
- `-`: Subtraction
- `*`: Multiplication
- `/`: Division
- `==`: Equality
- `<`: Less than
- `>`: Greater than
