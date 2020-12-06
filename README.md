# Emergency Vehicle Dispatch System (DAA Spring 2018)

# PROJECT AIM
To design an emergency vehicle dispatching system (given the three different types of emergency vehicles being Ambulance the first one, Fire Truck the second and Police car the third one), and to implement an algorithm that processes one request after the other to find the nearest available emergency vehicle

# LANGUAGE USED - JAVA

# INTRODUCTION
To design an emergency vehicle dispatching system, we initially started collecting and building the vehicle location, vehicle request data in separate text files. To utilize the above considered data, we generated few algorithms including Dijkstra’s algorithm for vehicle requests, searching vehicles and dispatching of the vehicles. Thus, the shortest path between the required and the available zip codes of the vehicles is found using Dijkstra’s algorithm and the output is taken out in a file.

# ALGORITHMS USED
* Dijkstra’s Algorithm – The purpose of this algorithm is to find the shortest path between the nodes in a graph. For example, if the nodes of the graph represent zip codes and edge path costs represent driving distances between pairs of zip codes connected by a direct road, Dijkstra's algorithm can be used to find the shortest route between one zip code and all other zip codes.
* In this algorithm, we first start at the initial node which is set to zero and all the remaining nodes are to be set to infinity where we create few unvisited nodes package, and from the current node we consider all the edges and the respective distances are calculated. After this, the node is to be marked as visited, and is now removed from the list of the unvisisted nodes and thus this process is therefore continued until all the edges are visited once and therefore the shortest path is thus finally attained.

# ALGORITHM EFFICIENCY
Here the overall time complexity of Dijkstra’s Algorithm is taken as O(E). Here we are storing the vertices in a Tresset and so our algorithm works on the basis of a treeset which gives us the time complexity of:
<center>O(E + VlogV)</center>

# CONCLUSION
Thus, the conclusion of the project is that we found the shortest path using the Dijkstra’s Algorithm and also an algorithm is implemented that processes one request after the other and the nearest available emergency vehicle is found. 
