# Sudoku (C++)

A console Sudoku puzzle game written in C++ as a Data Structures project.

## Features

- Three difficulty levels: Easy, Medium, Hard
- Board printed with 3x3 box separators
- Move validation (row, column and number must be 1-9, no duplicates in row/column)
- Clear a cell you filled in; cells from the initial puzzle are locked
- Completion message when the puzzle is solved

## Build and run

```bash
g++ Sudoku.cpp -o Sudoku
./Sudoku
```

On Windows: `Sudoku.exe`

## Controls

Enter `row column number` (each 1-9) to place a number, `0` as the number to clear a cell, or `-1` to go back.
