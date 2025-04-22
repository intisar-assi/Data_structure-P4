# Router Network Path Finder

## Overview

This C program simulates a network of routers and helps users find the shortest path between two routers using two popular algorithms:

- **Breadth-First Search (BFS)** — Suitable for finding the path with the fewest hops.
- **Dijkstra’s Algorithm** — Calculates the path with the least total latency.

The program reads router connections and latencies from a file and constructs an undirected graph using an adjacency matrix.

---

## Features

- Load routers and their connections from a file.
- Use **BFS** to find the path with the minimum number of routers.
- Use **Dijkstra’s Algorithm** to find the path with the minimum total latency.
- Outputs the results to both the console and a file named `shortest_distance.txt`.

---

## Input File Format

Each line of the file must follow this format:
RouterA-RouterB-Latency
