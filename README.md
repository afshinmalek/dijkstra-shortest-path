<div align="center">

# 🗺️ Dijkstra Shortest Path - Nearest Field Station

### Java · Graph Algorithms · Priority Queues

Dijkstra's algorithm over a 50-node weighted graph, assigning each customer to the nearest field station and printing the route.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Graph Algorithms](https://img.shields.io/badge/Graph_Algorithms-5382A1?style=for-the-badge&logoColor=white)
![Priority Queue](https://img.shields.io/badge/Priority_Queue-6E4C13?style=for-the-badge&logoColor=white)

</div>

## What it does

| Feature | Detail |
|---|---|
| Dijkstra's algorithm | Shortest paths from field stations 7, 14, 25, 28, and 40 |
| Indexed min-priority queue | Efficient decrease-key support via `IndexMinPQ` |
| Weighted graph | 50-node graph with weighted edges |
| Route output | Prints the shortest route to each assigned customer |

## Run

```bash
javac *.java
java ShortestPath
```

## Files

- `ShortestPath.java` - Dijkstra's algorithm and driver
- `Edge.java`, `EdgeWeightedGraph.java` - weighted graph representation
- `IndexMinPQ.java` - indexed minimum priority queue
- `G50.java` - the 50-node graph data

> Originally a Data Structures & Algorithms (CIS 27) project, extracted here as a standalone repo from [java-algorithms-and-concurrency](https://github.com/afshinmalek/java-algorithms-and-concurrency).
