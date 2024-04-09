# Conway's Game of Life

## Overview

Conway's Game of Life is a cellular automaton devised by John Horton Conway in 1970. Implemented in Java, this project simulates the game on a console application, allowing users to set initial configurations and observe how they evolve over generations. The game follows simple rules that determine the birth, survival, and death of cells on a rectangular grid.

## Features

- **Console-based Simulation**: Runs in the terminal or command prompt, displaying the grid and generations.
- **Customizable Initial State**: Users can set the initial state of the grid by specifying alive cells.
- **Automatic Evolution**: Once the initial state is set, the game evolves automatically, following the standard rules of Conway's Game of Life.

## Rules

1. **Birth**: A cell that is dead at time `t` will be alive at time `t+1` if exactly three of its eight neighbors were alive at time `t`.
2. **Death**: Each cell with one or no neighbors dies, as if by solitude. Each cell with four or more neighbors dies, as if by overpopulation.
3. **Survival**: Each cell with two or three neighbors survives for the next generation.
