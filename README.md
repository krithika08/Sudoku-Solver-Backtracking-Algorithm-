Sudoku-Solver-Backtracking-Algorithm
Python code to solve the Sudoku puzzle using the backtracking algorithm

This code was implemented for a project under Advanced Algorithms Course(UE20CS311),PES UNIVERSITY.

The structure of the puzzle is very simple, especially the classic puzzle. This essay is mainly focused on classic puzzle of a 9X9 grid. There already exist a number of digits in the board that make the puzzle solvable. It means that some numbers are already placed in the Sudoku board before starting. The board consists of 81 cells, which is divided into nine 3X3 sub boards and each 3X3 sub board is called “box” or “region”. The main concept of the game is to place numbers from 1 to 9 on a 9X9 board so that every row, column and box contains any numbers but once, 
that is, the numbers are not repeated more than once. 


This project accepts an input of 81 characters long string of numbers from 0 to 9, where 0 represents an empty cell on the Sudoku Board. The input is taken from a sudoku problem. The algorithm's goal is to swap out all the zeros for appropriate numbers so that the full Sudoku puzzle can be solved. In order to do this task conventionally, the processor must, in the worst case, test every one of the 2*10^77 potential combinations. Therefore, one of the finest solutions to this problem is the **Backtracking Algorithm**, which may solve it in a comparably shorter amount of time.

The code can be checked for various inputs by modifying the puzzles.py file and can be verified using the answers.py file.

How to run the project?
Download/clone this repository and extract all the files
Run solve_sudoku.py file using python ,([Python 3.0](https://www.python.org/download/releases/3.0/) and above OR [Python 2.2](https://www.python.org/download/releases/2.2/) and above) may be used.
Command to run:
python run solve_sudoku.py
