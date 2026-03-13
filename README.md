# Pathfinding Algorithm Visualizer


Course: Intelligent Systems </br>
Framework provided by course staff.
Search algorithms implemented by me.

**Technologies used:** Python, Pygame, Graph Search Algorithms


## About

The application visualizes how different search algorithms find paths in a weighted grid environment. An agent must navigate from a start position to a goal position while minimizing path cost across different terrain types.
The environment is represented as a grid map containing different terrain types with associated traversal costs.

### Terrain types include:
- Road (cost 2)
- Grass (cost 3)
- Snow (cost 5)
- Sand (cost 7)
- Mud (cost 21)
- Water (cost 101)
  
The agent can move in four directions: up, right, down, left.



## Getting Started

**Requirements:**
Python 3.x
pygame

**Install pygame:**
pip install pygame

**Run the simulation:**
python main.py [map] [agent]
**Example:**
python main.py maps/map0.txt AStar



## Example run of A* algorithm in the simulation:

<img width="597" height="650" alt="image" src="https://github.com/user-attachments/assets/8af2d9b0-5f16-46f8-b487-81d13a2d4b08" />
