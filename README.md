# DELHI METRO RAIL APP

Please don't get confused, this is NOT a mobile or graphical application!

This is a simple C++ program that takes the source and destination station names of the Delhi Metro from the user and displays the fare and the shortest metro route to reach the destination. It will also provide a metro map for better navigation.

The idea is implemented using Graph and Heap data structures. The graph has nodes and edges. Nodes represent metro stations and contain information like station name, the metro corridor, and the connecting lines. Edges (the connections between two nodes) represent the distance between stations, and the cost of each edge is equal to the distance between the two connecting stations (nodes).

By using algorithms such as Dijkstra, Breadth-First Search (BFS), Depth-First Search (DFS), etc., the shortest path between the source station and the destination station is calculated. The fare is based on the total distance traveled. Finally, the program displays the metro route and the total fare.
Components:

    Main.cpp: Contains the primary code including graph creation, user input, and route calculation.
    Heap.cpp: Contains the heap implementation, required for Dijkstra's algorithm.
## That was all... You are all set to work on the project!!!!  
	
