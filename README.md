# Eight Puzzle Solver

This Python script provides implementations of three search algorithms - Breadth-First Search (BFS), Depth-First Search (DFS), and A* Search (AST) - to solve the classic Eight Puzzle problem.

## Prerequisites

- Python 3.x
- tqdm (for progress bars during search)

Install tqdm using pip:

`pip install tqdm`


## Usage

Run the script `eight_puzzle_solver.py` with Python, providing the method and initial board configuration as command-line arguments, or simply run the script and follow the prompts.


- `method`: Choose from `bfs`, `dfs`, or `ast`.
- `initial_board`: Enter the initial board configuration separated by commas. For example, `1,2,3,4,5,6,7,8,0`.

If no arguments are provided, the script will prompt you to enter the method and initial board configuration interactively.


## Output

The script will display the following information upon completion:

- Resulting moves to reach the goal state
- Cost of the path
- Number of nodes expanded during the search
- Search depth
- Maximum search depth reached
- Total execution time

Additionally, the script will generate an `output.txt` file containing the same information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Derick Gustavo Andrighetti**
- GitHub: [@Rideckszz](https://github.com/Rideckszz)
- Date: 14/03/2024



