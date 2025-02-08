# Tic-Tac-Toe AI Algorithms Comparison

This repository contains a Python implementation of various AI algorithms for playing Tic-Tac-Toe. The algorithms implemented include:

- **Minimax**: A classic decision-making algorithm that explores all possible moves to determine the best one.
- **Alpha-Beta Pruning**: An optimized version of Minimax that reduces the number of nodes evaluated by pruning branches that cannot influence the final decision.
- **Evaluation-Based**: A heuristic-based approach that evaluates the board state using a scoring system to make decisions.
- **Monte Carlo Tree Search (MCTS)**: A probabilistic algorithm that simulates random games to determine the best move.

## Features

- **TicTacToe Class**: A game environment that manages the board state, validates moves, checks for a winner, and displays the board.
- **Algorithm Implementations**: Each algorithm is implemented as a function that takes the current game state and returns the best move.
- **Simulation Function**: A function to simulate matches between different algorithms and determine the winner.
- **Performance Statistics**: A function to run multiple matches between two algorithms and collect performance statistics, including win rates and average move times.
