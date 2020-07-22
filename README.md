# Breadth first search algorithm
Breadth first search (BFS) implementation is shown on an example database to find out how many 'degrees of separation' apart two actors are.
The large versions of the databases can be downloaded from the IMDb database. Here there is only smaller versions of each.

I'm interested in finding the shortest path between any two actors by choosing a sequence of movies that connects them. For example, the shortest path between Jennifer Lawrence and Tom Hanks is 2: Jennifer Lawrence is connected to Kevin Bacon by both starring in “X-Men: First Class,” and Kevin Bacon is connected to Tom Hanks by both starring in “Apollo 13.” I can frame this as a search problem: our states are people. Our actions are movies, which take us from one actor to another. Our initial state and goal state are defined by the two people we’re trying to connect. By using breadth-first search, we can find the shortest path from one actor to another.

Run as: python3 degrees.py <Database Folder>
Here, the database folder is 'small' so run as 'python3 degrees.py small'
