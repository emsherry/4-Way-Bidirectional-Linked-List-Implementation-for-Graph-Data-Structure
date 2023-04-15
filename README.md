# Graph Data Structure

This project implements a Graph data structure using a 4-way linked list to store phone numbers of users. It includes functions to add a user, delete a user, display all users, and search for a user data.

## Description

The Graph data structure is used to represent a collection of nodes (vertices) that are connected by edges. The edges represent the relationships between the nodes. In this implementation, we use a 4-way linked list to store phone numbers of users. Each vertex in the graph represents a user and its adjacency list represents the phone numbers associated with that user.

## Functions

The following functions are implemented in this project:

- `createGraph(int V)`: This function creates a new graph with V vertices.
- `addEdge(Graph *graph, int src, int dest)`: This function adds an edge between vertices `src` and `dest` in the graph.
- `printGraph(Graph *graph)`: This function prints the adjacency list representation of the graph.
- `deleteUser(Graph *graph, int user)`: This function deletes the user with the given index from the graph.
- `displayUsers(Graph *graph)`: This function displays all the users in the graph.
- `searchUser(Graph *graph, int user)`: This function searches for the user with the given index in the graph.

## Usage

To use this implementation of Graph data structure, you need to follow these steps:

1. Create a new graph using `createGraph(int V)` function.
2. Add edges between vertices using `addEdge(Graph *graph, int src, int dest)` function.
3. Display the adjacency list representation of the graph using `printGraph(Graph *graph)` function.
4. Use `deleteUser(Graph *graph, int user)` function to delete a user from the graph.
5. Use `displayUsers(Graph *graph)` function to display all the users in the graph.
6. Use `searchUser(Graph *graph, int user)` function to search for a user in the graph.

## Example

The following example demonstrates the usage of this Graph data structure:

int main()
{

int totalVertices = 4;

Graph *graph;

graph = createGraph(totalVertices);


addEdge(graph, 0, 1);

addEdge(graph, 0, 2);

addEdge(graph, 0, 3);

addEdge(graph, 1, 3);

addEdge(graph, 2, 3);


printGraph(graph);

deleteUser(graph, 2);

displayUsers(graph);


searchUser(graph, 3);


}


This code creates a new graph with 4 vertices, adds edges between vertices, prints the adjacency list representation of the graph, deletes user with index 2, displays all users in the graph, and searches for the user with index 3.```


