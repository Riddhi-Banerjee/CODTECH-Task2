# CODTECH-Task2
Name: RIDDHI BANERJEE
Company: CODTECH IT SOLUTIONS
ID: CT08EYU
Domain: C PROGRAMMING LANGUAGE
Duration: December 20th,2024 to January 20th,2025
Project Overview: 
Project Overview: Temperature Conversion Program
Project Title:
Temperature Conversion Program: Celsius, Fahrenheit, and Kelvin

Objective:
The objective of this project is to create a program that can convert temperatures between three common scales: Celsius, Fahrenheit, and Kelvin. The program will take user input for a temperature in one of the scales and then provide the corresponding temperature in the other two scales. This project aims to practice basic programming concepts such as user input, conditionals, mathematical operations, and output formatting.

Features:
User Input: The user will be prompted to input a temperature and specify the scale (Celsius, Fahrenheit, or Kelvin). The program will validate the input to ensure it is a valid number and that the scale is one of the three supported.
Temperature Conversion:

Based on the user’s selected scale, the program will convert the input temperature to the other two scales.
The following conversion formulas will be used:
Celsius to Fahrenheit:
𝐹 = ( 𝐶 × 9/5 ) + 32

Celsius to Kelvin:
𝐾=𝐶+273.15

Fahrenheit to Celsius:
𝐶 = ( 𝐹 − 32 ) × 5 / 9

Fahrenheit to Kelvin:
𝐾 = ( 𝐹 − 32 ) × 5 / 9 + 273.15

Kelvin to Celsius:
𝐶 = 𝐾 − 273.15

Kelvin to Fahrenheit:
𝐹 = ( 𝐾 − 273.15 ) × 9 / 5 + 32

Output: 
The program will display the converted temperature values for the other two scales based on the user input.
User Interface: The program will run in a terminal or command-line interface, providing clear instructions and feedback to the user.

Error Handling: The program will handle invalid inputs gracefully, such as non-numeric values or unsupported temperature scales.

Requirements:
Programming Language: C programming language.
Input Validation: Ensure proper handling of invalid inputs, such as non-numeric data or unsupported temperature scales.
Clear Output: Ensure that the converted temperatures are displayed clearly and formatted properly.
Technical Details:
Functions: 
Define functions to handle each conversion, such as celsius_to_fahrenheit(), fahrenheit_to_celsius(), etc.
Define a main function to handle the program flow, including gathering input, calling conversion functions, and displaying results.
User Interaction: 
The user will be asked to inputProgramming Language:

1. C Programming Language: 
The primary language used for this project is C, a powerful and efficient programming language that is widely used for system-level programming. C provides low-level memory manipulation capabilities, making it suitable for tasks requiring performance optimization. It will be used to implement the temperature conversion logic, handle user input, and produce output.
Integrated Development Environment (IDE): 
2. Code::Blocks, Dev-C++, Visual Studio, or Eclipse: 
These are popular IDEs that provide a development environment for C programming. They offer features like syntax highlighting, debugging, and code completion to enhance the development process. Alternatively, a simple text editor like Sublime Text or Notepad++ can be used alongside the GCC compiler for compiling and running the C code.
3. Compiler:
GCC (GNU Compiler Collection): GCC is a widely used open-source compiler for C and C++ that will be used to compile the C code into an executable. It provides optimization options and ensures the program runs efficiently.
4. Standard Libraries: 
stdio.h: The Standard Input/Output library in C will be used for user interaction. The printf() function will be used to display output, and the scanf() function will be used to gather user input.
stdlib.h: This library will provide useful functions such as exit() for program termination in case of critical errors and memory management functions if needed.
5. Mathematical Operations:
No external math library is required: The program will rely on basic arithmetic operations available in C (addition, subtraction, multiplication, division) to handle the temperature conversions. These operations will be used to implement the conversion formulas.
6. User Input and Output: 
scanf() function: This standard library function will be used to read input from the user. It will capture the numeric value of the temperature and the scale (Celsius, Fahrenheit, or Kelvin).
printf() function: This function will be used to display the results of the temperature conversion, outputting the values in a clear and readable format.
7. Error Handling: 
Basic error handling: In C, error handling can be achieved through simple conditional statements (like if-else) to validate inputs. Invalid inputs (non-numeric data or unsupported temperature scales) will be detected, and appropriate error messages will be displayed to the user.
exit() function: In case of critical errors (e.g., invalid temperature scale input), the exit() function from the stdlib.h library can be used to terminate the program.
8. Command Line Interface (CLI):
The program will be run in a command-line interface (CLI), where the user will enter temperature values and select the scale (Celsius, Fahrenheit, or Kelvin) using textual input. The program will output the converted temperatures in the terminal or console window.
9. Error Handling: 
Implement error handling for invalid inputs, such as non-numeric values and incorrect temperature scales.

Conclusion:
This temperature conversion program will serve as a fundamental exercise in working with user input, functions, and mathematical formulas. It will provide a clear understanding of how to work with different temperature scales and perform conversions in programming.
