# 70. Climbing Stairs

![alt text](image-28.png)

## Problem Description

You are climbing a staircase. It takes n steps to reach the top.

Each time you can either climb 1 or 2 steps. In how many distinct ways can you climb to the top?

## Approach

* if n is 1 dp[1] is 1, same for 2
* for every state the number of steps will be the sum of the prev 2 steps



## Time & Space Complexity

* **Time:** O(n)
* **Space:** O(1)
