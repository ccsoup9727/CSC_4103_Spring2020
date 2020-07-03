<——! README !—>

Name:Campbell, Casey
Email: ccamp65@lsu.edu
Project: PA-1 (multithreading)
Instructor: Feng Chen
Class: cs4103-sp20
Login: cs410313

The submitted program is a Sudoku Solution Validator that takes a designated input file, and then uses pthreads in order to validate a given Sudoku puzzle.

In order to run the c file: 

1.) The current file to be ran is set as sudoku.txt, which is the puzzle the program will default to solving.

2.) If you wish to use a different input file, add your sudoku.txt file to the workspace. Then where sudoku.txt is typed, replace with your filename. Otherwise, change the open statement to match your file path, like so: 

fp = fopen("sudoku.txt", mode);

3.) When the file is read, the program systematically checks the text file and validates all rows and columns until the puzzle is solved. 

4.) Output should be as pictured in the included screenshot “expected results” included with this folder. 