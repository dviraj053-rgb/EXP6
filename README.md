# EXP6
Aim: The overarching aim of this experiment was to comprehensively study and apply Python's conditional statements (if, elif, else) to solve various logical problems. This included tasks such as classifying numbers (positive/negative/zero, even/odd), comparing multiple values (finding the largest), assigning grades based on scores, determining leap years, and performing date increment operations.

Theory: The theoretical foundation of this experiment lies in Boolean logic and the control flow mechanisms provided by conditional statements in Python. Key concepts explored include:

Comparison Operators: (>, <, ==, >=, <=, !=) for evaluating relationships between values.
Logical Operators: (and, or, not) for combining multiple Boolean expressions into more complex conditions.
Modulo Operator (%): Essential for divisibility checks, particularly in determining even/odd numbers and certain aspects of leap year calculations.
if-elif-else Structure: The core construct for executing different blocks of code based on whether specific conditions are met. The sequential evaluation of if and elif conditions, and the fallback else block, were central to implementing decision-making logic.
Date Handling: While the datetime module offers robust functionality for date manipulation, the experiment also delved into manual date calculations using string splitting and if statements, demonstrating how complex logical rules (like month lengths and leap years) can be implemented from first principles.
String Manipulation: Functions like .lower(), len(), isalpha(), and split() were used to process string inputs for tasks like character classification and date parsing, highlighting the interplay between string methods and conditional logic.
Algorithm (General Approach): For each problem, the general algorithmic approach involved:

Input Acquisition: Prompting the user for necessary data (numbers, characters, dates, scores). (e.g., input(), int(), float())
Data Processing/Validation: Converting input types, normalizing data (e.g., .lower() for characters), and sometimes validating format (e.g., try-except for dates).
Conditional Logic Application: Applying if-elif-else statements to evaluate conditions based on the problem's requirements.
Simple comparisons (e.g., number > 0).
Divisibility checks (e.g., number % 2 == 0).
Compound conditions using and/or (e.g., leap year logic (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)).
Ordered range checks (e.g., grade calculation elif score >= 80).
Iterative logic for date increment (e.g., checking day > max_days, then month > 12).
Output Generation: Printing the result of the conditional evaluation in a user-friendly format (e.g., print(f"...")).
Conclusion: This experiment successfully demonstrated the versatility and power of conditional statements in Python for controlling program flow and implementing decision-making logic. Through a series of practical examples, it reinforced the understanding of if-elif-else, comparison operators, logical operators, and the modulo operator. It also highlighted how different tools (like the datetime module vs. manual logic) can be employed to solve the same problem, each with its own advantages in terms of complexity and robustness. The ability to correctly structure these conditions is fundamental to writing effective and responsive Python programs that can handle varied inputs and scenarios.
