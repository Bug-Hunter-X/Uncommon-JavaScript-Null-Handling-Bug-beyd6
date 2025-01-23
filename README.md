# Uncommon JavaScript Null Handling Bug

This repository demonstrates a subtle bug in JavaScript related to null value handling. The `foo` function attempts to handle null values gracefully, but there might be edge cases or situations where this approach isn't ideal or sufficient.  The solution explores alternative strategies to improve the robustness and clarity of the code.

## Bug Description
The `bug.js` file contains a JavaScript function that adds two numbers. It attempts to handle cases where one or both of the inputs are null by returning 0. While this works in basic cases, it may not be the appropriate behavior in all scenarios.  For example, the function might need to throw an error, use a default value other than 0, or provide more informative feedback in case of null values.

## Solution
The `bugSolution.js` file provides a more robust approach to null handling.  It uses optional chaining (?.) and nullish coalescing (??) operators to improve the code's readability and prevent potential errors caused by unexpected null values.