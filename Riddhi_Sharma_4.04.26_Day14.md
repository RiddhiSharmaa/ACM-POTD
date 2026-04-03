# 24. Swap Nodes in Pairs

![alt text](image-12.png)

## Problem Description

Given a linked list, swap every two adjacent nodes and return its head. You must solve the problem without modifying the values in the list's nodes (i.e., only nodes themselves may be changed.)

## Approach

* handle base cases of no node and 1 node
* we make a dummy pointer and make it point to the 2nd node since we know that will be the new head(so we can return ans at the end easily)
* we initialise 2 pointers to point to the 1st node in the pair(t1) and to point to the second node in the pair(t2)
* swap t1 and t2
* use a prev pointer so that the next pair's 2nd node can be the connected with the previously swapped pair's second node


## Time & Space Complexity

* **Time:** O(n)
* **Space:** O(1)
