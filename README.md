# ALGORITHM-DESIGN
This project implements and analyzes various algorithms including Heap Sort, Selection Sort, Dijkstra's Shortest Path, Kruskal's Minimum Spanning Tree, and the 0/1 Knapsack problem, demonstrating their time and space complexities using custom-generated datasets.


# Algorithm Design & Analysis Project

## Overview
This project is a comprehensive implementation and analysis of various algorithms as part of the CCP 6214 Algorithm Design & Analysis course. The project covers several key algorithms and data structures, demonstrating their implementation, time complexity, and space complexity.

## Table of Contents
1. [Dataset Generation](#dataset-generation)
2. [Sorting Algorithms](#sorting-algorithms)
3. [Graph Algorithms](#graph-algorithms)
4. [Dynamic Programming](#dynamic-programming)

## Dataset Generation
Two types of datasets were generated for this project:

### Dataset 1
- Generated based on the student ID (1211101555)
- Six different datasets of varying sizes: 100, 1,000, 10,000, 100,000, 250,000, and 500,000
- Used for sorting algorithm analysis

### Dataset 2
- Generated based on the sum of other group members' student IDs (3633305231)
- Represents a graph with stars as nodes and distances between stars as edges
- Used for graph algorithms and dynamic programming problems
### Graph Representation

### RANDOM STAR DETAILS
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/3f8914e5-6589-4ceb-b2fa-b5fbe9355830" alt="Graph Image 1" width="600"/>
</p>

### EDGES
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/b739bf2d-4044-45cf-b1ba-2a3edfc0ca37" alt="Graph Image 2" width="600"/>
</p>

### GRAPH
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/f36e1f3b-7b04-4670-8437-07d824cace17" alt="Graph Image 3" width="600"/>
</p>




## Sorting Algorithms
Two sorting algorithms were implemented and analyzed:

### Heap Sort
- Implementation using a priority queue
- Time Complexity: O(n log n)
- Space Complexity: O(1) for in-place sorting, O(n) using priority queue

### Selection Sort
- Simple comparison-based sorting algorithm
- Time Complexity: O(n²)
- Space Complexity: O(1)

Both algorithms were tested on Dataset 1, and their performance was compared across different dataset sizes.

## Graph Algorithms
Two graph algorithms were implemented using Dataset 2:

### Dijkstra's Algorithm (Shortest Path)
- Finds the shortest paths from a source star to all other stars
- Time Complexity: O((n + m) log n)
- Space Complexity: O(n + m)
  
### SAMPLE OUTPUT
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/9ca8906e-fba9-4049-a304-e353fa0dfca0" alt="Graph Image 3" width="600"/>
</p>


### Kruskal's Algorithm (Minimum Spanning Tree)
- Finds the minimum spanning tree of the star graph
- Time Complexity: O(m log m)
- Space Complexity: O(n + m)

Where n is the number of stars/vertices and m is the number of edges.

### SAMPLE OUTPUT
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/1a65f938-d903-4837-bd40-9fe9e99a3d4d" alt="Graph Image 3" width="600"/>
</p>


## Dynamic Programming
The 0/1 Knapsack problem was solved using dynamic programming:
### SAMPLE OUTPUT
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/541c2668-c348-4e0d-90eb-2a0938f216d6" alt="Graph Image 3" width="600"/>
</p>
<p align="center">
  <img src="https://github.com/Low0000/ALGORITHM-DESIGN/assets/123613860/27cf37e4-c0fd-4f2c-a570-d7aa2db462ee" alt="Graph Image 3" width="600"/>
</p>




### 0/1 Knapsack
- Maximizes the total profit of items (stars) placed in a knapsack without exceeding the weight capacity
- Time Complexity: O(nW)
- Space Complexity: O(nW)

Where n is the number of stars and W is the maximum weight capacity.
