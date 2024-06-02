# Pathfinding Visualization with A* Algorithm

## Overview

This project visualizes the A* pathfinding algorithm using Pygame. It allows users to create barriers on a grid and then find the shortest path between a start and end point. The project is interactive, enabling users to dynamically modify the grid and visualize how the algorithm navigates through it.

## Features

- **Interactive Grid Creation:** Click to place barriers, start, and end points on the grid.
- **Pathfinding Visualization:** Press the space bar to start the A* algorithm and watch it find the shortest path.
- **Grid Reset:** Press 'C' to clear the grid for a new instance.
- **Real-Time Updates:** See the algorithm's progress in real-time as it searches for the path.

## How to Use

1. **Run the Program:** Execute the Python script to start the Pygame window.
2. **Create Barriers:** Click on the grid to place barriers. These represent obstacles that the algorithm must navigate around.
3. **Set Start and End Points:** Right-click to set the start point and middle-click to set the end point.
4. **Start the Algorithm:** Press the space bar to begin the A* pathfinding process. The algorithm will search for the shortest path and display it.
5. **Clear the Grid:** Press 'C' to clear the grid and start over.

## A* Algorithm Overview

The A* (A-star) algorithm is a widely used pathfinding and graph traversal algorithm, known for its efficiency and accuracy. It uses a combination of the actual distance from the start node to the current node (known as the g-cost) and a heuristic estimate of the distance from the current node to the end node (known as the h-cost). The sum of these two costs (f-cost) is used to determine the next node to explore, ensuring that the algorithm finds the shortest path.

### Key Concepts of A*:

- **g(n):** The actual cost from the start node to the current node.
- **h(n):** The heuristic estimated cost from the current node to the end node. Typically, the Manhattan distance or Euclidean distance is used.
- **f(n) = g(n) + h(n):** The total cost function that the algorithm minimizes.

A* maintains a priority queue of nodes to explore, always expanding the node with the lowest f-cost first. This allows it to efficiently find the shortest path while considering both the cost to reach the node and an estimate of the cost to reach the goal.

## Dependencies

- Pygame

## Installation

1. Clone this repository:
   ```bash
   git clone [https://github.com/nightwing02/A-star]
   ```
2. Navigate to the project directory:
   ```bash
   cd A-star
   ```
3. Install the required dependencies:
   ```bash
   pip install pygame
   ```
4. Run the application:
   ```bash
   python main.py
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the open-source community and the numerous resources available for learning about pathfinding algorithms and Pygame development.

---

Feel free to modify this template to better fit your project's specifics.
