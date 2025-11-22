# Algorithms and Data Structures

This repository contains a collection of classic algorithms and data structures implemented as part of the advanced programming exam. Each solution includes theoretical complexity analysis (Time & Space) and test cases.

## Project Structure

### 1. Data Structures
* **Linked List Reversal**: In-place reversal of a singly linked list.
    * *Complexity*: Time **O(N)**, Space **O(1)**.
* **Red-Black Tree Balancing**: Implementation of balancing logic (rotations and recoloring) for a self-balancing binary search tree.
    * *Complexity*: Insertion/Deletion **O(log N)**.

### 2. Algorithms
* **Stock Trading (k transactions)**: A dynamic programming approach to find maximum profit with at most `k` transactions.
    * *Complexity*: Time **O(n * k)**, Space **O(n * k)**.
* **Bellman-Ford Algorithm**: Single-source shortest paths in graphs with potential negative edge weights and cycle detection.
    * *Complexity*: Time **O(V * E)**, Space **O(V)**.
* **Hotel Guest Management**: A sweep-line algorithm to find the maximum number of concurrent guests using arrival and departure events.
    * *Complexity*: Time **O(N log N)** (due to sorting), Space **O(N)**.
* **Relevance Ranking System**: A high-performance ranking system using linear combinations of features with support for real-time updates.
    * *Complexity*: Search **O(k + log d)**, Update **O(log d)**.

## How to Run
All solutions are provided as Jupyter Notebooks (`.ipynb`).
1. Install requirements: `pip install jupyter`
2. Open any notebook: `jupyter notebook algorithms/<folder>/<filename>.ipynb`