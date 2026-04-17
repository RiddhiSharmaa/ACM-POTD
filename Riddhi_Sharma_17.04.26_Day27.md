# 236. Lowest Common Ancestor of a Binary Tree

![alt text](image-25.png)

## Problem Description

Given a binary tree, find the lowest common ancestor (LCA) of two given nodes in the tree.

## Approach

we use *dfs* in this question

* if node is equal to p or q return node
* LCA is the first node when both left and right return non null
* or if p or q is LCA, it will be returned first
* if either left or right node is found return that



## Time & Space Complexity

* **Time:** O(n)
* **Space:** O(h)
