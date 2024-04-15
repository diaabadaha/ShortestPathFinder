# ShortestPathFinder

## Overview
ShortestPathFinder is a C program developed for the COMP2421 course. It employs Dijkstra’s and Breadth-First Search (BFS) algorithms to determine the shortest paths between two user-specified cities. The program reads city data, constructs a graph, and calculates the shortest route, detailing the full path and total distance using both algorithms.

## Repository Contents
- `ShortestPathFinder.c`: The C source file containing the implementations of Dijkstra’s and BFS algorithms along with all necessary functions to find the shortest path.
- `Project 4 Spring 2023.pdf`: The project brief, detailing the requirements and expectations for the program.

## Features
- Load graph data from `cities.txt` to form a network of connected cities.
- Prompt for user input to specify source and destination cities.
- Calculate and display the shortest route between cities using Dijkstra’s and BFS algorithms, including the distance between each pair of cities along the path and the total shortest distance for Dijkstra’s algorithm.
- Save the calculated route and distance information to `shortest_distance.txt` upon exiting the program.

## How It Works
The program operates through a menu-driven interface:
1. **Load Cities**: Constructs the graph structure from the provided `cities.txt` file.
2. **Enter Source**: Accepts user input to set the source city.
3. **Enter Destination**: Computes and displays the shortest paths to the destination city using both Dijkstra’s and BFS algorithms.
4. **Exit**: Outputs the shortest path information to `shortest_distance.txt` and terminates the program.

## Contribution
This is an individual project for academic assessment, meant to showcase the student's problem-solving abilities using graph theory algorithms. External contributions should be limited to academic support and feedback.
