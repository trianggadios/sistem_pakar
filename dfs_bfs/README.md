# DFS (depth-first search)

 1. we have the **graph** or tree with node like A, B, C, D, E, and F.
 2. first checking is node has visited bye the program, if not visited it will stack into list with the variable called **visited**.
 3. then it will check is the node same with the goals? if yes it will print the path of node visited, if no then the program will loop in node values list called as **neighbour **
 
# BFS (breadth-first search)
 1. also we have **graph** as the tree source.
 2. the difference from DFS is BFS will check the cross node, in this case node A have 2 neighbour B and C, if we use DFS, the DFS will check the B neighbour, but not for BFS, BFS will check cross neighbour too (C), In conclusion, BFS will check all nodes on each layer, while DFS will check all the first children or first neighbour of the nodes
