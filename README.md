# Implementation-of-RRT-Star-for-Path-Finding
Implementing an RRT* algorithm for dynamic path finding with a graphical user interface (GUI). Below is a simplified example using Python, Pygame for the graphical interface, and a basic RRT* algorithm. This example assumes the drone needs to find a path in a 3D space with both static and dynamic obstacles.

# Required Libraries
!pip install pygame numpy

# RRT* Algorithm
Here's a simplified version of the RRT* algorithm with dynamic pathfinding. This implementation will include:

A basic RRT* algorithm.
Dynamic re-planning to avoid obstacles.
Pygame for visualization.

# Explanation
Node Class: Represents a point in the space.
RRTStar Class: Implements the RRT* algorithm with methods for path planning, collision checking, and rewiring.
Dynamic Obstacle Handling: A rectangle moves within the screen, bouncing off the edges, and the path is re-planned periodically considering its updated position.
Pygame Visualization: Visualizes the obstacles, nodes, and paths in a Pygame window.
