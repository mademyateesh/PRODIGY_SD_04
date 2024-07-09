# PRODIGY_SD_04

Create a program that solves Sudoku puzzles automatically. The program should take an input grid representing an unsolved Sudoku puzzle and use an algorithm to fill in the missing numbers. It should use backtracking or other suitable techniques to explore possible solutions and find the correct arrangement of numbers for the puzzle. Once solved, the program should display the completed Sudoku grid.

explanation : is_valid() function

This function checks if a given number can be placed in a specific position on the board. It takes three arguments:

board: The 2D list representing the Sudoku board
row: The row index of the position to check
col: The column index of the position to check
num: The number to check if it can be placed in the position
The function returns True if the number can be placed in the position, and False otherwise.

Here's what the function does:

It checks if the number already exists in the same row or column. If it does, it returns False.
It checks if the number exists in the same 3x3 sub-grid. If it does, it returns False.
If the number passes both checks, it returns True.
solve_sudoku() function

This function uses the backtracking algorithm to solve the Sudoku puzzle. It takes one argument:

board: The 2D list representing the Sudoku board
The function returns True if a solution is found, and False otherwise.
