# MazeSolver
MazeSolver is a C++ project that solves a given maze using pathfinding algorithms. The program reads a maze structure from a file, then identifies the path from the starting point to the destination using a selected algorithm. This project is ideal for those interested in understanding graph traversal techniques.


# Features
Maze Representation: Reads maze structure from a file and displays it on the console.
Pathfinding Algorithms: Implements algorithms like Depth-First Search (DFS) and Breadth-First Search (BFS) to find the path from start to end.
Customizable Maze Input: Input a maze of any size, with start and end points designated in the file.
Error Handling: Checks for invalid input files and handles path errors.
Setup

# Clone this repository:
git clone https://github.com/princekrmishra/MazeSolver.git
cd MazeSolver

# Usage
The maze file should have:
S for the starting point
E for the endpoint

# for walls
. for paths

# Example:
S . # . E
# . # . #
# . . . #
The program will output the maze with the solved path if available.

# License
This project is licensed under the MIT License. See LICENSE for more information.
