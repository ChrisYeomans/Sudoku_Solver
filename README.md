# Sudoku Solver

Written in c++. Will take input with one positive integer, a square number determining the size of the sudoku. 

Input will then be a series of integers, row by row of the input sudoku, blank squares given by -1.

**Current Algorithm Idea**:
Go through whole grid for each number, 1-9, and fill in definites.
If nothing has been filled in for a whole round of numbers take simultaneous paths for one the the smallest options, killing a path when is becomes impossible.