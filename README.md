# Connect-4 AI Project

This is an AI-driven implementation of Connect-4. It features a Heuristic AI that evaluates board positions and plays against a Random Agent.

## Project Structure
- **Main.py**: Entry point to run the game.
- **Connect4.py**: Contains the game environment and main logic.
- **BoardHeuristic.py**: Implementation of the heuristic AI.
- **RandomAgent.py**: Logic for the random agent.
- **GameController.py**: Controls gameplay and interactions.
- **Utility.py**: Utility functions for board operations.
- **Constants.py**: Defines constants used throughout the project.

## How to Run
1. Clone the repository.
2. Ensure Python 3 and NumPy are installed.
3. Run the following command:
    ```
    python Main.py
    ```
### Testing Minimax Algorithms

1. Navigate to the directory containing `MINIMAX_tester.py`.
2. Ensure all dependencies are installed.
3. Run the following command to test Minimax algorithms:
    ```bash
    python MINIMAX_tester.py
    ```

### Testing Monte Carlo Tree Search

To test the performance of the Monte Carlo Tree Search algorithm:

1. Navigate to the directory containing `MonteCarloTreeSearch.py`.
2. Ensure all dependencies are installed.
3. Run the following command to test the Monte Carlo Tree Search algorithm:
   ```bash
   python MonteCarloTreeSearch.py
   
### Testing Monte Carlo Tree Search vs. Minimax with Alpha-Beta Pruning

This script allows you to compare the performance of Monte Carlo Tree Search (MCTS) and the Minimax algorithm with Alpha-Beta Pruning in a Connect-4 game.

1. Navigate to the directory containing `AlphaBeta_Monte.py`.
2. Ensure all dependencies are installed, including `numpy`.
3. Run the following command:
   ```bash
   python AlphaBeta_Monte.py
