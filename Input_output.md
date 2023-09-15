#  Number Operation Evaluator

## Problem Statement
Given two integer numbers, return their product only if the product is equal to or lower than 1000. Otherwise, return their sum.

## Problem Description
Write a Python program that takes two integer numbers as input, performs two operations (multiplication and addition), and prints the result based on certain conditions.

## Concept
- Input and Output
- Basic Arithmetic Operations

## Input
- Two integer numbers, `n1` and `n2`, where (-1000 <= n1, n2 <= 1000).

## Output
- If the product of `n1` and `n2` is less than or equal to 1000, print the product.
- Otherwise, print the sum of `n1` and `n2`.

## Example
**Example 1:**
```plaintext
Name: Multiply or Add

Input:
n1 = 20
n2 = 30

Output:
The result is 600
```

**Example 2:**
```plaintext
Name: Multiply or Add

Input:
n1 = 40
n2 = 30

Output:
The result is 70
```

**Example 3:**
```plaintext
Name: Multiply or Add

Input:
n1 = -500
n2 = 800

Output:
The result is 300
```

## Constraints
- The result should be an integer.
- If the product of `n1` and `n2` is greater than 1000, return the sum.
- The result should always be within the range of a 32-bit signed integer.
