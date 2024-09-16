Escape Room Game using A* Algorithm
This is a Python-based escape room game that generates a random maze where the player must find the shortest path from a starting point to a randomly generated end point. The A* algorithm is used to calculate the optimal path, and the maze includes randomly placed obstacles.

Features
Maze generation of any size specified by the user.
Random obstacle placement based on user input.
Randomly generated end point that avoids obstacles.
A* pathfinding algorithm to find the shortest path.
Visual representation of the maze, path, start, and end points using Matplotlib.

How to Play
Run the game.
Input the size of the maze (e.g., 10 for a 10x10 maze).
Input the number of obstacles to place in the maze.
The game will generate a maze and attempt to find the shortest path using A*.
The start point is marked in green, the end point in blue, and the path (if found) in red.
A* Algorithm
The A* algorithm is used to find the shortest path in the maze. It employs:

A priority queue for nodes to explore.
A Manhattan distance heuristic to estimate the cost to the end.
Path reconstruction from the end point to the start point after finding the optimal path.
