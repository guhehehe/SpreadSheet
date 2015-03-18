# SpreadSheet

Simple spread sheet implementations in different languages

## Problem
Implement a spread sheet program to support basic operations.

Your program should take two integers as the length and width of the spread sheet, each column should be labeled
alphabetically, and each row should be labeled numerically. For example, the cell in row 3 and column 4 should be
identified by D3.

After defining the size of the spread sheet, your program should populate each cell with the input on each line as the
value of the cell, in a left to right, top to bottom manner. For example, a 4 x 4 spread sheet should expext 4 lines of
input to have its cells filled, with the order of the cell A1, A2, B1, B2 on each line.

The value of the cell can be in the following form:

* Value: Text or numerical, for example, "apple", "12"
* Variable: A reference to another cell, for example, "A3", "B2"..., the referenced cell must contain numerical values
* Expression: addition, substraction, multiplication, division or their combination, for example, "A3 + 4 \* B2"

Your Program should also perform circular reference in a sensitive way, which means that a circular reference should be
discovered as soon as possible.
