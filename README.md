# Activity-10

Edges:
A--B
A--C
B--D
B--E
C--F
E--F
graph is demonstrated as:

       A
      / \
     B   C
    / \   \
   D   E-- F
   Whic is undirected, so the edges go both ways. 

   Task 2:
   I implemented the grpah using an adjacency lis. This list sotres each vertex with a list of its connected neighbors. Breadth-forst search uses a queue, it starts with one vertex, then to close points and expands on out. 
Depth-first search uses a stack or recursion. It goes as deep as possible down one path before backtracking.

Task 3: 

Both BFS and DFS have the same time complexity:

O(V+E)

V means the number of vertices.  
E means the number of edges.

This is because both algorithms visit every vertex once and check every edge.

The space complexity is also:

O(V)
