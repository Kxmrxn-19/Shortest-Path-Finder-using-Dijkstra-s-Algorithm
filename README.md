
Here's a README for your Dijkstra's Algorithm Pathfinding project using Pygame:

Shortest Path Finder using Dijkstra's Algorithm
This project is a visual representation of Dijkstra's algorithm implemented in Python using the Pygame library. The algorithm finds the shortest path between two points on a grid, taking into account barriers that the path cannot cross.

Features
Visualize the execution of Dijkstra's algorithm on a grid.
Interactively set the start and end points.
Create barriers to simulate obstacles.
Reset the grid to try different scenarios.
Requirements
Python 3.x
Pygame library
Installation
Install Python: Ensure Python 3.x is installed on your machine. You can download it from python.org.

Install Pygame: Install the Pygame library using pip:

sh
Copy code
pip install pygame
Clone the Repository: Clone this repository to your local machine:

sh
Copy code
git clone https://github.com/your-username/shortest-path-finder.git
cd shortest-path-finder
Usage
Run the Program: Start the program by running the Python script:

sh
Copy code
python shortest_path_finder.py
Setting Start and End Points:

Left-click on any grid cell to set the start point (orange).
Left-click on another grid cell to set the end point (turquoise).
Creating Barriers:

Left-click on grid cells to create barriers (black) that the algorithm cannot pass through.
Removing Barriers:

Right-click on grid cells to remove barriers or reset start/end points.
Start the Algorithm:

Press the SPACE key to start the visualization of Dijkstra's algorithm.
Reset the Grid:

Press the F key to reset the grid and start over.
File Structure
shortest_path_finder.py: Main script containing the implementation of the grid, nodes, and Dijkstra's algorithm visualization.
Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.
