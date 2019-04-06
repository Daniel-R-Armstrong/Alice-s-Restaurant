#Graph basics

Graphs are structures that map relations between objects. The objects are referred to as nodes and the connections between them as edges in this tutorial. Note that edges and nodes are commonly referred to by several names that generally mean exactly the same thing:

node == vertex == point
edge == arc == link

The starting graph is undirected. That is, your edges have no orientation: they are bi-directional. For example: A<--->B == B<--->A.
By contrast, the graph you might create to specify the shortest path to hike every trail could be a directed graph, where the order and direction of edges matters. For example: A--->B != B--->A.

The graph is also an edge-weighted graph where the distance (in miles) between each pair of adjacent nodes represents the weight of an edge. This is handled as an edge attribute named "distance".

Degree refers to the number of edges incident to (touching) a node. Nodes are referred to as odd-degree nodes when this number is odd and even-degree when even.

The solution to this CPP problem will be a Eulerian tour: a graph where a cycle that passes through every edge exactly once can be made from a starting node back to itself (without backtracking). An Euler Tour is also known by several names:

Eulerian tour == Eulerian circuit == Eulerian cycle
A matching is a subset of edges in which no node occurs more than once. A minimum weight matching finds the matching with the lowest possible summed edge weight.

NetworkX: Graph Manipulation and Analysis
NetworkX is the most popular Python package for manipulating and analyzing graphs. Several packages offer the same basic level of graph manipulation, notably igraph which also has bindings for R and C++. However, I found that NetworkX had the strongest graph algorithms that I needed to solve the CPP.

https://www.datacamp.com/community/tutorials/networkx-python-graph-tutorial

(not my work)
