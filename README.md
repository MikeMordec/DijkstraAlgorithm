DijkstraAlgorithm
Description

DijkstraAlgorithm is a Python script that implements Dijkstra's algorithm to find the shortest path between vertices in a weighted graph. This script demonstrates graph traversal and shortest path calculation.
Features

    Creates a graph with nodes and weighted edges.
    Computes the shortest path from a source vertex to all other vertices.
    Outputs the shortest distances from the source vertex and the path to a specified destination.

Usage

    Clone the repository:

    bash

git clone https://github.com/your-username/DijkstraAlgorithm.git

Navigate to the project directory:

bash

cd DijkstraAlgorithm

Run the script:

bash

    python dijkstra_algorithm.py

    The script will output the graph, shortest distances from the source vertex, and the shortest path to the specified destination vertex.

Example Output

plaintext

Michael Mordec, 7/24/22, Lab 14, CSC 242:
The Graph
---------
A = {'B': 1, 'C': 4, 'D': 2}
B = {'A': 9, 'E': 5}
C = {'A': 4, 'F': 15}
D = {'A': 10, 'F': 7}
E = {'B': 3, 'J': 7}
F = {'C': 11, 'D': 14, 'K': 3, 'G': 9}
G = {'F': 12, 'I': 4}
H = {'J': 13}
I = {'G': 6, 'J': 7}
J = {'H': 2, 'I': 4}
K = {'F': 6}
---------
Shortest path distances from A : {'A': 0, 'B': 1, 'C': 4, 'D': 2, 'E': 6, 'F': 9, 'G': 18, 'H': 8, 'I': 12, 'J': 7, 'K': 12}

The path between A to H :
A <- D <- B <- E <- J <- H

Requirements

    Python 3.x
