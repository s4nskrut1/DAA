# DAA — Algorithms, Patterns & Complexity

> A collection of algorithm implementations exploring searching, sorting, greedy strategies, graph algorithms, dynamic programming, and backtracking.

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp" alt="C++" />
</p>

---

## The algorithm board

Instead of treating the repository as a list of programs, here is the problem-solving map behind it:

```text
                         ALGORITHMS
                              │
          ┌───────────────────┼───────────────────┐
          ▼                   ▼                   ▼
      SEARCHING            SORTING             GRAPHS
          │                   │                   │
   Linear · Binary     Merge · Quick      Dijkstra · Floyd
                                          Prim · Kruskal
          │                   │                   │
          └───────────────────┼───────────────────┘
                              ▼
                       OPTIMISATION
                              │
                   ┌──────────┴──────────┐
                   ▼                     ▼
                 GREEDY             BACKTRACKING
                   │                     │
          Knapsack · Merge        N-Queens
          Pattern · Fractional
```

---

## Search first

### Linear Search

A straightforward sequential search through a collection — useful as the baseline against which more efficient searching strategies can be understood.

### Binary Search

A divide-and-conquer search that works on sorted data by repeatedly narrowing the search interval.

---

## Sorting strategies

| Algorithm | Core idea |
|---|---|
| **Merge Sort** | Divide the input, sort the halves, then merge them |
| **Quick Sort** | Partition around a pivot and recursively sort the partitions |

Both implementations provide a useful comparison between two classic divide-and-conquer sorting approaches.

---

## Graph algorithms

This repository includes several approaches to graph problems:

- **Dijkstra's Algorithm** — shortest paths from a source in a weighted graph
- **Floyd–Warshall** — all-pairs shortest paths using dynamic programming
- **Prim's Algorithm** — minimum spanning tree construction
- **Kruskal's Algorithm** — minimum spanning tree construction using edge selection

```text
GRAPH PROBLEMS
     │
     ├── Shortest Path
     │      ├── Dijkstra
     │      └── Floyd–Warshall
     │
     └── Minimum Spanning Tree
            ├── Prim
            └── Kruskal
```

---

## Greedy & optimisation

### Fractional Knapsack

Select fractions of items according to their value-to-weight ratio to maximise the total value within a capacity constraint.

### Knapsack

A discrete optimisation problem where item selection is constrained by capacity.

### Optimal Merge Pattern

A greedy strategy for combining files or sorted sequences while minimising the total merge cost.

---

## Backtracking

### N-Queens Problem

A classic constraint-satisfaction problem: place `N` queens on an `N × N` chessboard so that no two queens attack each other.

It is a compact example of **backtracking** — make a choice, test it, and backtrack when the choice leads to a dead end.

---

## Complexity lens

One of the main ideas behind DAA is not simply *whether* an algorithm works, but **how efficiently it works as the input grows**.

| Technique | Typical time complexity |
|---|---|
| Linear Search | `O(n)` |
| Binary Search | `O(log n)` |
| Merge Sort | `O(n log n)` |
| Quick Sort | `O(n log n)` average |
| Dijkstra | depends on implementation |
| Floyd–Warshall | `O(V³)` |

The repository's implementations make these trade-offs easier to study directly in code.

---

## Repository map

```text
DAA/
│
├── Searching
│   ├── Linear Search
│   └── Binary Search
│
├── Sorting
│   ├── Merge sort
│   └── Quick Sort
│
├── Graph Algorithms
│   ├── dijkstra
│   ├── floyd - warshall's algoprithm
│   ├── prims algorithm
│   └── kruskal's algorithm
│
├── Optimisation
│   ├── knapsack
│   ├── fractional knapsack
│   └── optimal merge pattern
│
└── Backtracking
    └── N Queens Problem
```

The original program names are preserved so the repository remains directly usable alongside the corresponding coursework.

---

## What's inside

**12 implementations** covering:

`searching` · `sorting` · `graphs` · `greedy algorithms` · `dynamic programming` · `backtracking` · `optimisation`

---

<p align="center">
  <sub>Design & Analysis of Algorithms · Algorithmic Problem Solving</sub>
</p>
