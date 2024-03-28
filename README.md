# Sudoku Solver Project

## Introduction

This project is a game that allows users to solve a Sudoku puzzle, aiming to recreate the experience of solving Sudoku puzzles found in newspapers. In this project, we've implemented a Sudoku solver using Java and Java Swing for the graphical user interface (GUI).

## Features

- **Grid Layout**: The game consists of a 9x9 grid of boxes that can be filled with digits from 1 to 9. Each grid is further divided into 3x3 subgrids.
  
- **Buttons**: The game includes buttons for various functionalities:
  - Reset Button: Empties the whole grid.
  - Exit Button: Closes the execution of the game.
  - Solution Button: Fills the grid with expected solutions.
  - Hint Button: Verifies the correctness of moves made by the user.

- **Interactive Grid**: Users can interact with the grid by clicking on the buttons to fill digits.

## Technologies Used

- **Java Language**: The project is primarily coded in Java.
  
- **Java Swing**: Java Swing is used to build the GUI application. It provides components such as buttons, labels, and text fields for designing the UI.
  
- **Maven**: The project is structured using Maven, a build automation tool primarily used for Java projects.

## Project Structure

The project is structured as follows:

- `src/`: Contains the source code for the Sudoku Solver.
  - `Main.java`: Main class responsible for launching the application and setting up the GUI.
  - `SudokuSolver.java`: Contains the logic for solving Sudoku puzzles.
  - Other classes and resources related to the GUI and functionality.

## Building and Running the Project

To run this project, ensure you have the Java Development Kit (JDK) installed on your system.

1. **Clone this repository** to your local machine: git clone
https://github.com/YashasMangalore/Sudoku_Solver

3. **Navigate** to the project directory: cd
Sudoku_Solver/tree/master/mavenproject1/src/main/java/com/mycompany/mavenproject1
 
5. **Compile** the Java files: javac Sudoku.java

6. **Run** the project: javac Sudoku.java

## Usage
Upon running the program, you'll be presented with the Sudoku grid and various buttons for interacting with the game. Here's how you can use the buttons:

Fill Digits: Click on the grid buttons to fill digits from 1 to 9.
Reset: Click the reset button to empty the grid and start over.
Exit: Click the exit button to close the game.
Solution: Click the solution button to automatically fill the grid with expected solutions.
Hint: Click the check moves button to verify the correctness of your moves.
