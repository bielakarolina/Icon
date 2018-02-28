# Reduction of Logical Expressions
## Input data
### The program loads logical expressions from the standard input.
### Each input line contains one expression. There may be spaces in the expression, program ignores them.
### If the line contains an incorrect logical expression, the following line appears on the standard output: ERROR

## Program
###  The program reduces logical expressions. Logic B is a reduced expression of A if:
### - length of expression (number of characters needed to save it) B is smaller than the length of expression A,
### - for any set of variables appearing in expression A, both expressions give the same result.
### If the program can not reduce the expression, it prints the input expression.

## Results
### The program prints the reduced expressions to the standard output.
