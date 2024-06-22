# JavaScript Loop and CSV Parsing Lab

## Introduction
This repository contains the solutions for the JavaScript Loop and CSV Parsing Lab. The lab is divided into several parts, showcasing the use of different types of loops, conditional statements, and data manipulation techniques in JavaScript.

## Objectives
- Use for loops to iterate a specific number of times.
- Use for-of loops to iterate through iterable data-like strings.
- Use while loops to iterate based on a condition.
- Use the break and continue statements to control loop flow.
- Transform and manipulate data according to specifications.

## Part 1: Fizz Buzz
The Fizz Buzz problem is solved using a for loop. The code iterates through numbers 1 to 100 and prints:
- "Fizz" if the number is divisible by 3.
- "Buzz" if the number is divisible by 5.
- "Fizz Buzz" if the number is divisible by both 3 and 5.
- The number itself if it is not divisible by 3 or 5.

## Part 2: Prime Time
This part finds the next prime number greater than a given number `n`. The code uses a while loop to iterate through numbers, starting from `n+1`, and checks for primality using a helper function `isPrime()`. The loop exits as soon as it finds the next prime number.

## Part 3: Feeling Loopy
This part involves parsing CSV data. The code processes a CSV string, iterating through each character, storing each cell's data, and logging each row. It assumes that:
- There are 4 cells per row.
- Cells are separated by commas.
- Rows are separated by newline characters.


