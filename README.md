# Path Visualizer Web App

![image](https://github.com/AnurajBhaskar47/path_finding_visualiser/assets/97795939/a9023feb-0024-4992-9d4b-77fd246facd9)

The **Path Visualizer Web App** is a web-based tool developed using React.js that allows users to visualize various path-finding algorithms, including Dijkstra's algorithm, A*, Breadth-First Search, Greedy Breadth-First Search, Depth-First Search, Convergent Swarm Algorithm, and Bidirectional Swarm Algorithm. This app provides an interactive and educational way to understand how these algorithms work and find the shortest path between two points on a grid.

## Table of Contents
<ul>
  <li>Demo</li>
  <li>Features</li>
  <li>Installation</li>
  <li>Usage</li>
  <li>Algorithms</li>
</ul>

### Demo
To see the Path Visualizer Web App in action, you can check out the live demo [here.](https://graphpathvisualiser.netlify.app/)
<br><br>
[  <img src="https://github.com/AnurajBhaskar47/path_finding_visualiser/assets/97795939/90e31e6d-dbae-4404-8c61-75eae2e1fe27" width="500" height="250" alt="DiscussIt Screenshot">](https://graphpathvisualiser.netlify.app/)

### Features
<ul>
  <li>Visualize various path-finding algorithms in real-time.</li>
  <li>Create custom grids and obstacles.</li>
  <li>Start and stop algorithms at any time.</li>
  <li>See detailed step-by-step visualization of the algorithm's progress.</li>
  <li>Interactive user interface for an easy understanding of the algorithms.</li>
  <li>Fast and efficient algorithm implementations.</li>
  <li>Responsive design, suitable for both desktop and mobile devices.</li>
</ul>

### Algorithms
The Path Visualizer Web App currently supports the following path-finding algorithms:

<details><summary>Dijkstra's Algorithm</summary> 
     <ul>
      <li>Dijkstra's algorithm is a weighted graph search algorithm that finds the shortest path between a source node and all other nodes in a graph.</li>
      <li>It explores nodes in order of their distance from the source node, guaranteeing the shortest path when all edge weights are non-negative.</li>
    </ul></details>
<details><summary>A* Algorithm</summary> 
    <ul>
      <li>A* is a heuristic-based search algorithm that combines the best features of Dijkstra's algorithm and Greedy Best-First Search.</li>
      <li>It uses a heuristic function to estimate the cost of reaching the destination, allowing it to explore paths that seem the most promising first.</li>
    </ul></details>
<details><summary>Breadth-First Search</summary> 
     <ul>
      <li>BFS is an unweighted graph search algorithm that explores all nodes at a given depth level before moving on to the next level.</li>
      <li>It is guaranteed to find the shortest path in unweighted graphs.</li>
    </ul></details>
<details><summary>Greedy Breadth-First Search</summary>
    <ul>
      <li>Greedy BFS is a variant of BFS where it uses a heuristic to prioritize nodes for exploration.</li>
      <li>Unlike A*, it doesn't consider the total cost to reach a node, making it less optimal for certain scenarios.</li>
    </ul></details>
<details><summary>Depth-First Search (DFS)</summary>
    <ul>
      <li>DFS explores as far down a branch as possible before backtracking.</li>
      <li>It doesn't guarantee the shortest path and may explore long paths before shorter ones.</li>
    </ul></details>
<details><summary>Convergent Swarm Algorithm</summary>
    <ul>
      <li>The Convergent Swarm Algorithm is a swarm-based search algorithm inspired by the behavior of birds and insects.</li>
      <li>It uses a swarm of agents to explore the search space and converge toward the destination.</li>
    </ul></details>
<details><summary>Bidirectional Swarm Algorithm</summary>
    <ul>
      <li>The Bidirectional Swarm Algorithm is an extension of the Convergent Swarm Algorithm.</li>
      <li>It explores the search space from both the source and destination simultaneously, aiming to meet in the middle.</li>
    </ul></details>
Each algorithm has its unique characteristics and can be selected from the user interface for visualization.

### Installation

To run the Path Visualizer Web App locally on your machine, follow these steps:

1. Clone the repository to your local machine using Git:

```bash
git clone https://github.com/AnurajBhaskar47/path_finding_visualiser.git
```

2. Change to the project directory:

```bash
cd path-visualizer
```

3. Install the project dependencies using npm (Node Package Manager):

```bash
npm install
```

### Usage
After completing the installation steps, you can start the development server:

```sql
npm start
```
This will launch the web app in your default web browser. You can then interact with the app to visualize different path-finding algorithms.





