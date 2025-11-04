# Pacman-Search

## Overview
This project contains the implementation of search algorithms for the CS188 Artificial Intelligence course (Fall 2025) at UC Berkeley. The goal of the project is to build various search strategies to solve maze-like puzzles using Pacman as the agent.

## Project Description
In Project 1, "Search," we are asked to implement classical search algorithms such as Depth-First Search (DFS), Breadth-First Search (BFS), Uniform Cost Search (UCS), and A* Search. The project emphasizes understanding state space, frontier management, and path cost evaluation with heuristics.

The goal is to navigate Pacman through mazes efficiently to reach target points while applying these algorithms correctly.

## Features
- Implemented DFS, BFS, UCS, and A* search algorithms.
- Functionality to visualize Pacman's path using the provided graphical interface.
- Custom heuristics for A* Search.
- Modular code structure to extend future projects.

## Installation
- Python 3.8 or higher is required.
- You can run the project in Termux or any Linux/Windows/Mac environment.
- Install dependencies (if any) with:
  
  ```
  pip install -r requirements.txt
  ```
- Run the project scripts using:
  
  ```
  python pacman.py -p SearchAgent -a fn=depthFirstSearch
  ```

## Usage
- Execute specific search algorithms by changing the function argument (`fn`) in the command line.
- Explore different mazes and test algorithm efficiency.
- Refer to the CS188 course documentation for detailed instructions and grading.

## Project Structure
```
/pacman-search
├── pacman.py          # Main executable and visualization
├── search.py          # Your search algorithm implementations
├── layout.py          # Maze layouts
├── README.md          # This file
└── tests/             # Unit tests for search algorithms
```

## Contributing
This project is for educational purposes as part of the CS188 course and contributions outside the course requirement are not encouraged.

## License
This project is licensed under the MIT License.

---
