# 83. Remove Duplicates from Sorted List

![alt text](image-10.png)

## Problem Description

Given the head of a sorted linked list, delete all duplicates such that each element appears only once. Return the linked list sorted as well.


## Approach

* we traverse the linked list
* check for every node's next node, whether its value is equal to the previous node
* if so, update current node's next and make it point to the next node's next
* delete the node
* move temp to next



## Time & Space Complexity

* **Time:** O(n)
* **Space:** O(1)
