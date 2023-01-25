# Intersection of Two Linked Lists

[Link to the original problem on Leetcode](https://leetcode.com/problems/intersection-of-two-linked-lists/)

## Problem

Given the heads of two singly linked-lists `headA` and `headB`, return the node at which the two lists intersect. If the two linked lists have no intersection at all, return `null`.

The test cases are generated such that there are no cycles anywhere in the entire linked structure.

Note that the linked lists must retain their original structure after the function returns.

### Example

Input: 
`intersectVal = 8, listA = [4,1,8,4,5], listB = [5,6,1,8,4,5], skipA = 2, skipB = 3`

Output: 
`Intersected at '8'`

Explanation: 
The intersected node's value is 8. There are 2 nodes before the intersected node in A; There are 3 nodes before the intersected node in B.

Input: 
`intersectVal = 2, listA = [1,9,1,2,4], listB = [3,2,4], skipA = 3, skipB = 1`

Output: 
`Intersected at '2'`

Explanation: 
- The intersected node's value is 2. There are 3 nodes before the intersected node in A; There are 1 node before the intersected node in B.

Input: 
`intersectVal = 0, listA = [2,6,4], listB = [1,5], skipA = 3, skipB = 2`

Output: 
`No intersection`

Explanation: 
- The two lists do not intersect, so return null.

### Constraints
- The number of nodes of `listA` is in the `m`.
- The number of nodes of `listB` is in the `n`.
- `1 <= m, n <= 3 * 10^4`
- `1 <= Node.val <= 10^5`
- `0 <= skipA < m`
- `0 <= skipB < n`
- `intersectVal` is `0` if `listA` and `listB` do not intersect.
- `intersectVal == listA[skipA] == listB[skipB]` if `listA` and `listB` intersect.

### Follow up
- Could you write a solution that runs in O(m + n) time and use only O(1) memory?
