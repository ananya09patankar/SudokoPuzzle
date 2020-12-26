# SudokoPuzzle
Solving Sudoku puzzles using backtracking method

ALGORITHM:
i. Input is taken in the form of 9 rows.

ii. Every row of input consists of numbers separated by a space.


iii. Every row is appended to the list sudoku.

iv. Call the function solveSudoku().

v. Find the empty location in the grid by calling functionfindEmptyLocation().

vi. Use a loop to generate numbers from 1 to 9.

vii. Call a function check() to check if the number is safe to enter or not.

viii. Inside the function check(), the rows, columns and the sub grid is checked
for any repetition using the function usedInRow(), usedInCol(), usedInMiniGrid() respectively.

ix. If the number assigned satisfies all the three conditions, then it is assigned to that cell.

x. If the Sudoku is solved, then print the Sudoku using printGrid() function else print “No solution exists”.

