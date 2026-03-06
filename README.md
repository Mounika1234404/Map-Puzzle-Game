# Map Puzzle Game – Algorithm Design Paradigms

## Overview

This project implements a two-player puzzle game inspired by puzzles from **Simon Tatham’s Portable Puzzle Collection**. The game is designed as a **Human vs CPU** system where the player competes against a computer agent.

The CPU gameplay strategies are implemented using multiple **algorithm design paradigms**, demonstrating how different algorithms can influence decision-making in puzzle-solving environments.

## Objective

The objective of this project is to explore and implement different algorithmic approaches for solving puzzle-based problems and evaluate their efficiency in game-playing strategies.

## Features

* Two-player puzzle game (Human vs CPU)
* CPU decision-making using multiple algorithm design paradigms
* Graph-based representation of the puzzle
* Sorting techniques integrated into game logic
* Progressive development through multiple review stages

## Algorithms Implemented

The CPU gameplay strategy is implemented using the following paradigms:

### Greedy Algorithm

Selects the locally optimal move at each step to progress toward solving the puzzle efficiently.

### Divide and Conquer

Breaks the puzzle into smaller subproblems and solves them recursively.

### Dynamic Programming

Stores previously computed states and reuses them to optimize puzzle-solving.

### Backtracking

Explores all possible puzzle configurations and backtracks when a path does not lead to a valid solution.

## Game Model

* **Player 1:** Human player
* **Player 2:** CPU (algorithm-based decision making)

The CPU analyzes the current puzzle state and selects moves based on the implemented algorithmic strategy.

## Graph Representation

The puzzle is represented as a **graph structure** where:

* Nodes represent puzzle states
* Edges represent possible transitions or moves

This representation helps implement algorithm-based strategies efficiently.

## Sorting in Game Logic

Sorting techniques are integrated into the game logic to organize possible moves and improve CPU decision-making.

## Project Development Reviews

### Review 1

* Game selection and model design
* Proof of concept implementation
* Graph representation of the puzzle
* Greedy algorithm implementation

### Review 2

* Improvements from previous version
* Divide & Conquer implementation
* Sorting integration in game logic
* Algorithm performance analysis

### Review 3

* Further system improvements
* Dynamic Programming implementation
* Backtracking implementation
* Algorithm analysis and comparison

## Technologies Used

* Programming Language: (Add your language here e.g., Python / Java / C++)
* Simon Tatham Puzzle framework
* Graph-based data structures
* Algorithm design paradigms

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/repository-name.git
```

2. Navigate to the project directory:

```bash
cd repository-name
```

3. Run the main game file:

```bash
python main.py
```

*(Replace with the correct command based on your programming language.)*

## Learning Outcomes

* Practical implementation of algorithm design paradigms
* Understanding of graph-based problem representation
* Application of algorithms in game development
* Comparative analysis of algorithm efficiency

## Author

**Mounika Dirisala**
Computer Science and Engineering Student
