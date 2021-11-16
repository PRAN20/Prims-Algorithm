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

## Example :
- Construct a minimum spanning tree of the graph given in the following figure by using prim's algorithm.
![image](https://user-images.githubusercontent.com/65455865/141949536-337ea2dd-05bf-47c2-82e5-bf4688c0080f.png)

## Solution:
- Choose a starting vertex B.
- Add the vertices that are adjacent to A. the edges that connecting the vertices are shown by dotted lines.
- Choose the edge with the minimum weight among all. i.e. BD and add it to MST. Add the adjacent vertices of D i.e. C and E.
- Choose the edge with the minimum weight among all. In this case, the edges DE and CD are such edges. Add them to MST and explore the adjacent of C i.e. E and A.
- Choose the edge with the minimum weight i.e. CA. We can't choose CE as it would cause cycle in the graph.
The graph produces in the step 4 is the minimum spanning tree of the graph shown in the above figure.

## The cost of MST will be calculated as;

- cost(MST) = 4 + 2 + 1 + 3 = 10 units.

