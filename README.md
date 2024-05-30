# UNDIRECTED-GRAPHS

An undirected Graph can e defined as a kind of Graph in which the node connecttions (Edges) do not have directions assigned to them. 

This codebase implements the feature of weighted edges foor it's graphs, i.e the 
weight of the edge(int) between two Nodes in the Tree taken into accojnt as a property of an object of the Node class.

The following are characteristics of Undirected Graphs: 
1. An undirected graph may contain loops, which are edges that connect a vertex to itself.
2. Degree of each vertex is the same as the total no of edges connected to it.
3. Edges in an undirected graph are bidirectional in nature.
4. In an undirected graph, there is no concept of a “parent” or “child” vertex as there is no direction to the edges.

In essence, Undirected Graphs allows for flexibility as they are versatile and may be used to describe a broad range of systems
Real life applications of Undirected Graphs include: 

1. Undirected graphs can be used to model social networks where User accounts are represented by nodes and the connections between them are represented by edges.
2.  Undirected graphs can also be used in traffic flow optimization to model the flow of vehicles on road networks.
3.  Undirected graphs can as well be used in Website analysis to analyze the links between web pages on the internet. Each web page is represented by a vertex, and each link between web pages is represented by an edge.


PRIM'S ALGORITHM--
Prim's algorithm is a good example of a 'Greedy algorithm' because it looks fro the best/cheapest way scenario at every step along the way.
The idea behind implementing the minimum spanning Tree is to maintain two sets of Nodes. 
The first set contains the Nodes already included in the minimum spanning Tree, and the other set contains the Nodes not yet included. 
At every step along the way, it considers all the edges that connect the two sets (The last added Node to the minimum spanning Tree and one of hter connected Nodes nto yet part of the minimum spanning Tree) and picks the minimum weight edge from these edges(In this code base, a priority queue is used to achieve this). 
After picking the minimum weighted edge, it moves the connected Node by this edge and adds to the set of the minimum spanning Tree.
