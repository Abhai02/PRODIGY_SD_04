# PRODIGY_SD_04
This Python program solves a 9x9 Sudoku puzzle using backtracking. The algorithm works as follows:

is_valid(board, row, col, num) – Checks if a number can be placed in a given cell without violating Sudoku rules.
solve_sudoku(board) – Uses recursion and backtracking to fill the board by trying numbers from 1 to 9 in empty cells. If a number leads to an unsolvable state, it backtracks and tries the next option.
print_board(board) – Displays the solved Sudoku board.
