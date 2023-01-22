# Merge k Sorted Lists

[Link to the original problem on Leetcode](https://leetcode.com/problems/merge-k-sorted-lists/)

## Problem

You are given an array of k linked-lists `lists`, each linked-list is sorted in ascending order.

Merge all the linked-lists into one sorted linked-list and return it.

### Example

Input: `lists = [[1,4,5],[1,3,4],[2,6]]`

Output: `[1,1,2,3,4,4,5,6]`

Explanation: The linked-lists are:
```
[
  1->4->5,
  1->3->4,
  2->6
]
```
merging them into one sorted list:
`1->1->2->3->4->4->5->6`

Input: `lists = []`

Output: `[]`

Input: `lists = [[]]`

Output: `[]`

### Constraints
- `k == lists.length`
- `0 <= k <= 104`
- `0 <= lists[i].length <= 500`
- `-10^4 <= lists[i][j] <= 10^4`
- `lists[i]` is sorted in ascending order.
- The sum of `lists[i].length` will not exceed 104.