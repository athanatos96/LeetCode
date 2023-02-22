# Binary Tree Zigzag Level Order Traversal

[Link to the original problem on Leetcode](https://leetcode.com/problems/binary-tree-level-order-traversal/)

## Problem

Given the root of a binary tree, return the zigzag level order traversal of its nodes' values. (i.e., from left to right, then right to left for the next level and alternate between).

### Example

Input: root = [3,9,20,null,null,15,7]
Output: [[3],[20,9],[15,7]]

Input: root = [1]
Output: [[1]]

Input: root = []
Output: []

### Constraints

- The number of nodes in the tree is in the range [0, 2000].
- -1000 <= Node.val <= 1000