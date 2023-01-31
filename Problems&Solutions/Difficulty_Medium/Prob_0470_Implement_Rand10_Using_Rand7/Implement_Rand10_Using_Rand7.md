# Implement Rand10() Using Rand7()


[Link to the original problem on Leetcode](https://leetcode.com/problems/implement-rand10-using-rand7/)

## Problem

Given the API rand7() that generates a uniform random integer in the range [1, 7], write a function rand10() that generates a uniform random integer in the range [1, 10]. You can only call the API rand7(), and you shouldn't call any other API. Please do not use a language's built-in random API.

Each test case will have one internal argument n, the number of times that your implemented function rand10() will be called while testing. Note that this is not an argument passed to rand10().
### Example

Input: n = 1
Output: [2]

Input: n = 2
Output: [2,8]

Input: n = 3
Output: [3,8,10]

### Constraints

- 1 <= n <= 10^5

Follow up:

- What is the expected value for the number of calls to rand7() function?
- Could you minimize the number of calls to rand7()?