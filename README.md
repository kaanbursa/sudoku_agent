# Solve Sudoku with AI

## Synopsis

The goal of the project is to solve sudoku puzzle's with various playing techniques.


## Naked_Twins
The naked twins strategy says that if you have two or more unallocated boxes
    in a unit and there are only two digits that can go in those two boxes, then
    those two digits can be eliminated from the possible assignments of all other
    boxes in the same unit.
## Elimination
The eliminate strategy says that if a box has a value assigned, then none
    of the peers of that box can have the same value.
## Only_choice
The only choice strategy says that if only one box in a unit allows a certain
    digit, then that box must be assigned that digit.
## Search
Apply depth first search to solve Sudoku puzzles in order to solve puzzles
    that cannot be solved by repeated reduction alone.


