# Prims-Algorithm

## Prim's Algorithm
Prim's Algorithm is used to find the minimum spanning tree from a graph. Prim's algorithm finds the subset of edges that includes every vertex of the graph such that the sum of the weights of the edges can be minimized.

Prim's algorithm starts with the single node and explore all the adjacent nodes with all the connecting edges at every step. The edges with the minimal weights causing no cycles in the graph got selected.

The algorithm is given as follows.

## Algorithm
- Select a starting vertex
- Repeat Steps 3 and 4 until there are fringe vertices
- Select an edge e connecting the tree vertex and fringe vertex that has minimum weight
- Add the selected edge and the vertex to the minimum spanning tree T
[END OF LOOP]
- EXIT
