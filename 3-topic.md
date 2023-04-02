# Tree

## What is a Binary Tree Data Structure?

A Binary Tree is defined as a tree data structure where each node has at most 2 children. Since each element
in a binary tree can have only 2 children, we typically name them the left and right child.

## Binary Tree Representation

A Binary tree is represented by a pointer to the topmost node (commonly known as the "rooot") of the tree. If
the tree is empty, then the value of the root is NULL> Each node of a Binary Tree contins the following parts:

1. Data
2. Pointer to the left child
3. Pointer to the right child

## Basic Operation On Binary Tree:

* Inserting an element.
* Removing an element.
* Searching for an element.
* Traversing the tree.

## Auxiliary Operation On Binary Tree

* Finding the height of the tree.
* Find the level of a node of the tree.
* Finding the size of the entire tree.

## Example: Check for BST

Given the root of a binary tree. Check whether it is a BST or not.

* The left subtree of a node contains only nodes with keys less than the node's key.
* The right subtree of a node contains only nodes with keys greater than the node's key.
* Both the left and right subtrees must also be binary search trees. 

**Input:**
   2
 /    \
1      3

**Output:** 1 

**Explanation:**
The left subtree of root node contains node
with key lesser than the root nodes key and 
the right subtree of root node contains node 
with key greater than the root nodes key.
Hence, the tree is a BST.

## Problem to Solve:

## Solution: