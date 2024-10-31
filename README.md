# Min-Conflicts 8-Queens Solver

A Python implementation of the min-conflicts algorithm to solve the 8-queens puzzle.

## Overview

This program implements the min-conflicts algorithm to solve the classic 8-queens puzzle, where eight queens must be placed on a chess board without any queen threatening another.

## Features

- Random initial state generation
- Min-conflicts local search implementation
- Visual board representation
- Configurable board size (works for n-queens)
- Step tracking for solution monitoring

## Usage

```python
# Create and solve an 8-queens puzzle
n = 8
max_steps = 1000
solution = min_conflicts(n, max_steps)
print_board(solution)
