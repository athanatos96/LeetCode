# Median of Two Sorted Arrays

## Problem

Given two sorted arrays `nums1` and `nums2` of size `m` and `n` respectively, return the median of the two sorted arrays.

The overall run time complexity should be `O(log(m+n))`.

[Link to the original problem on Leetcode](https://leetcode.com/problems/median-of-two-sorted-arrays/)

### Example

Input: `nums1 = [1,3]`, `nums2 = [2]`

Output: `2.00000`

Explanation: merged array = `[1,2,3]` and median is `2`.

Input: `nums1 = [1,2]`, `nums2 = [3,4]`

Output: `2.50000`

Explanation: merged array = `[1,2,3,4]` and median is `(2 + 3) / 2 = 2.5`.

### Constraints
- `nums1.length == m`
- `nums2.length == n`
- `0 <= m <= 1000`
- `0 <= n <= 1000`
- `1 <= m + n <= 2000`
- `-10^6 <= nums1[i], nums2[i] <= 10^6`
