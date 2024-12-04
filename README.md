# Maze Solver

Python application that generates and solves mazes using depth-first search. Built with Tkinter for visualization.

## Features
- Random maze generation
- Visual maze solving animation
- Configurable maze dimensions
- Path finding with backtracking

## Requirements
- Python 3.x
- Tkinter

## Usage
inside your terminal run:
```python main.py``` or ```python3 main.py```

## Files
- ```main.py``` - Entry point
- ```maze.py``` - Logic to generate maze and solve it
- ```cell.py``` - Create the cell object
- ```graphics.py``` - Visualization for Tkinter

## Installation
1. Clone the repository
2. Ensure Python 3.x is installed
3. Ensure Tkinter is installed
4. Run ```python main.py``` or ```python3 main.py```

## How It Works

This program generates a random maze using a depth-first search algorithm. It then attempts to solve it
by finding a path from entrance to exit. The solving process is visualized with red lines for the current
path and gray lines for backtracking. In the terminal it prints if the maze was solvable or not.