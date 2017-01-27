# Code for solving Assignment Model problem

A C++ code for solving the assignment model problem in operations research using the hungarian method.

Functions used-
1. input() - Takes input in matrix
2. print() - Displays the matrix values
3. reduce() - Row and Column reduction
4. zeroes() - Calculates number of zeroes in each row and column
5. cut() - Similiar to what drawing a line and 'cutting' a row or column
6. eliminate() - Calculate maximum number of zeroes from columns and rows
7. optimal() - Check for optimality of the solution
8. iterate() - Prepare for iteration in case of non-optimality of solution
9. assign() - Assignment of jobs to workers after reaching optimality
10. calculate(int, int) - Calculation of sum of zeroes in row and column of a zero element after previous assignments
11. balance() - Balance an unbalanaced assignment problem by adding rows or columns 
12. final() - Display final assignments and calculate total time
