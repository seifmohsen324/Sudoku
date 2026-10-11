# Sudoku in C

A console Sudoku game with predefined Easy, Medium, and Hard 9×9 boards. Players enter a row, column, and value; the program checks the selected cell and the row, column, and 3×3 region before accepting a move.

## Project files

```text
.
├── FinalSudoku.c
└── FinalSudoku.exe
```

## Build and run

With a C compiler:

```bash
gcc FinalSudoku.c -o sudoku
./sudoku
```

On Windows, run the generated executable as `sudoku.exe`. The checked-in `FinalSudoku.exe` is platform-specific.

Select a difficulty, then enter moves in the prompted comma-separated format, for example `1,4,7` for row 1, column 4, value 7. Rows and columns are numbered from 1 to 9.

## Scope

The puzzles are embedded in the C source. The project does not currently include a puzzle generator, solver, saved-game feature, or graphical interface.
