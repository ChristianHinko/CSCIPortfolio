[Back to Portfolio](./)

# Graph Adjacency Matrix

**Class:** Algorithms (CSCI 415)

**Grade:** A

**Language(s):** C++

**Source Code Repository:** [ChristianHinko/GraphAdjacencyMatrix](https://github.com/ChristianHinko/GraphAdjacencyMatrix)

(Please [email me](mailto:cthinkle9@csustudent.net?subject=GitHub%20Access) to request access.)

## Project Description

This project implements a graph in the form of an adjacency matrix and demonstrates it functionality along with some popular algorithms.

The user runs the program and provides the input file pathname as an argument. This input file populates the graph by adding edges with integer weight values between character vertices.

The program prints the adjacency matrix generated and calculates all shortest paths starting from vertex 'd' to all other vertices using dijkstra's algorithm.

## Design

The primary focus of this graph implementation was to provide the most compile-time-flexible structure with practical algorithm implementations.

The CTHGraphAdjacencyMatrix<> type is a fully functional graph compatible with any vertex data types and weight data types.

The CTHGraphAdjacencyMatrixFunctionLibrary provides algorithms DijkstraShortestPaths<>() and DepthFirstTraversal<>() which are generic to any type of adjacency matrix graph. They are also made of broken up functionality which makes their implementations easier to read and understand.

Something that sought to do was make my implementaiton practical by having DijkstraShortestPaths<>() return the entire path traveled - not just the minimized total weight traveled. This became a challenge of the project and an inefficiency of the algorithm but was worth it for the applicablility of my solution.

[Back to Portfolio](./)
