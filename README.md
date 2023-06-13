# Sudoku Helper with Hints in JavaScript

This is a Sudoku helper written in JavaScript that can help you solve any valid Sudoku puzzle. The solver uses Sudoku tricks such as obvious singles, doubles and triples, and hidden singles and doubles to help you find the solution.

## Getting Started

To use this Sudoku solver, follow these steps:

1. Clone the repository or download the source code.
2. Open the `index.html` file in your web browser.
3. Enter the Sudoku puzzle you want to solve in the input fields or go to https://virtualknight8.github.io/sudoku-solver/.
4. Click the Hint button to get the most possibly valid value for the cells chosen algorithmically by the program.
5. Click the Notes Button to see all possible values that are valid for each and every blank cells. The values change dynamically as you enter your own.
6. Click the New Game Button to get an entirely new puzzle set generated randomly by the algorithm.

The Sudoku tricks used by the solver are:

- Obvious Singles: If a cell has only one possible value, fill it in.
- Obvious Doubles: If two cells in a row, column, or box have the same two possible values, those values must go in those two cells and no others.
- Obvious Triples: If three cells in a row, column, or box have the same three possible values, those values must go in those three cells and no others.
- Hidden Singles: If a number can only go in one cell in a row, column, or box, fill it in.
- Hidden Doubles: If two numbers can only go in two cells in a row, column, or box, those numbers must go in those two cells and no others.

## Contributing

If you would like to contribute to this project, you can fork the repository and make changes as you see fit. If you have any suggestions or find any bugs, please open an issue on the repository or submit a pull request.
