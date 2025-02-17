# Sudoku-Generator-and-Solver


## Description
This is a Python-based Sudoku Generator and Solver application built using Tkinter. It allows users to generate Sudoku puzzles of different difficulty levels, solve them, validate their solutions, and even receive hints in the form of simple math problems.

## Features
- Generate Sudoku puzzles with three difficulty levels: Easy, Medium, and Hard.
- Solve the Sudoku puzzle automatically.
- Validate the user's solution against the correct one.
- Provide hints through mathematical operations.
- Interactive GUI with color-coded subgrids.

## Installation
### Prerequisites
Ensure you have Python installed on your system. You can download it from [Python's official website](https://www.python.org/).

### Required Libraries
This application uses Tkinter (which comes pre-installed with Python). If you're using a basic Python installation, you might need to install `tkinter` (for Linux-based systems):
```sh
sudo apt-get install python3-tk
```

## Usage
1. Run the script:
   ```sh
   python sudoku.py
   ```
2. Select the difficulty level (Easy, Medium, or Hard).
3. Click "Generate Sudoku" to create a puzzle.
4. Solve the puzzle manually or use the "Solve Sudoku" button to complete it automatically.
5. Validate your solution using the "Validate Sudoku" button.
6. Click "Hint" to receive a mathematical hint for a blank cell.

## Files
- `sudoku.py`: The main script containing the GUI, Sudoku generator, and solver logic.

## How It Works
- The Sudoku puzzle is generated using a backtracking algorithm.
- Numbers are removed based on the selected difficulty level.
- The solver applies a recursive backtracking approach to find a valid solution.
- Hints provide a math operation that results in the correct number for a selected blank cell.

## License
This project is open-source and available under the MIT License.

## Author
Akanksha Sharma

