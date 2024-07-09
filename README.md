# PRODIGY_SD_04

Explanation:
Grid Size: The Sudoku grid is a 9x9 matrix.
Input Grid: An example unsolved Sudoku grid is provided.
printBoard(): This method prints the Sudoku board in a readable format.
solveBoard(): This method uses backtracking to solve the Sudoku puzzle. It recursively tries to fill empty positions (denoted by 0) with numbers from 1 to 9, and if it encounters a valid configuration, it continues. If it encounters an invalid configuration, it backtracks.
isValidPlacement(): This method checks whether placing a number in a given position is valid according to Sudoku rules.
