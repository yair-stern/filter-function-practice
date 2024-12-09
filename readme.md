# Filter Function Practice

This project is a simple program designed to practice using the `filter` function in JavaScript. The program has no practical application; its sole purpose is to help developers understand and improve their skills with array filtering.

## Overview

The program performs the following tasks:

1. **Generate an Array**: Creates an array of 10 random numbers (both positive and negative).
2. **Apply Filters**: Filters the array based on four different conditions:
   - Negative numbers.
   - Numbers greater than 3.
   - Even numbers.
   - Odd numbers.
3. **Preserve Original Array**: The original array remains unchanged, while the results of each filter are stored in separate arrays.

## Filters

The program uses the `filter` function to create the following filtered arrays:

1. **Negative Numbers**: Includes only numbers less than 0.  
   Example: `[3, -5, -2, 8]` → `[-5, -2]`

2. **Numbers Greater Than 3**: Includes only numbers greater than 3.  
   Example: `[1, 5, -2, 7]` → `[5, 7]`

3. **Even Numbers**: Includes only numbers divisible by 2.  
   Example: `[2, 3, 4, 5]` → `[2, 4]`

4. **Odd Numbers**: Includes only numbers not divisible by 2.  
   Example: `[2, 3, 4, 5]` → `[3, 5]`

## Installation and Usage

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
