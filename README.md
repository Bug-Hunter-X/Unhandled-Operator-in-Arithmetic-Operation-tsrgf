# Unhandled Operator in Arithmetic Operation

This repository demonstrates a common JavaScript bug related to unhandled operators in a function that performs arithmetic operations. The original code only handles addition, subtraction, multiplication, and division, throwing an error for any other operator.  This can lead to unexpected behavior and crashes if the function is called with an unsupported operator.

The solution extends the function to include a more comprehensive approach or to explicitly handle the case for the modulo operator.

## Bug

The `operate` function is designed to perform basic arithmetic operations.  It does not handle the modulo operator (`%`) or other potential operators, resulting in an error.

## Solution

The solution addresses the issue by either using a more robust approach to handling operators or by explicitly handling the modulo operator as well.