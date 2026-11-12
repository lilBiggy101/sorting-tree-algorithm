# Binary Search Trees and Red-Black Trees

![C++](https://img.shields.io/badge/C%2B%2B-blue) ![Course](https://img.shields.io/badge/CS315-Algorithm%20Design-lightgrey)

## Overview
A C++ project implementing two tree-based data structures: a Binary Search Tree (BST) and a Red-Black Tree. Both are used to insert and delete values from numerical CSV datasets and traverse the results. Built for my CS315 Algorithm Design class.

## Concepts Covered
- Binary Search Trees: insertion, searching, deletion
- Recursive tree traversal, including in-order (LNR)
- Tree height
- Red-Black Trees: balancing, rotations, and recoloring

## BST vs. Red-Black Tree
| | BST | Red-Black Tree |
|---|---|---|
| Search / insert / delete (average) | O(log n) | O(log n) |
| Search / insert / delete (worst) | O(n) if the tree degenerates | O(log n), guaranteed by balancing |


## Project Structure
- `bst.cpp`: Binary Search Tree
- `redBlack.cpp`: Red-Black Tree
- `testrandom.csv`, `testBad.csv`: test datasets
- `deleteNodes.csv`: values to delete

## How to Run
```bash
git clone https://github.com/lilBiggy101/sorting-tree-algorithm.git
cd sorting-tree-algorithm
g++ -o bst bst.cpp
g++ -o redBlack redBlack.cpp
./bst <insert_file> <delete_file>
```
For example: `./bst testrandom.csv deleteNodes.csv`. The first file holds the values to insert and the second holds the values to delete.

## Technologies
- C++
- Standard Template Library (STL)

## What I Learned
- How to structure tree-based data structures to organize and traverse datasets.
- The trade-offs between a plain BST and a self-balancing tree, and how to implement each.
