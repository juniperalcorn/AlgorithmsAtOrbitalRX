# Picking Numbers

Given an array of integers, find the longest subarray where the absolute difference between any two elements is less than or equal to 1. Return the length of that array.

Example:
```
Input: [1,1,2,2,4,4,5,5,5]
Output: 5
```
Explanation: there are two subarrays that fit the criteria of absolute difference (`[1,1,2,2]` and `[4,4,5,5,5]`), but you should fine the subarray with greater length to satisfy the criteria for the output.

Example 2:
```
Input: [4,5,6,3,3,1]
Output: 3
```
Explanation: The subarray that fits the criteria is `[4,5,6]`.

Example 3:
```
Input: [1,2,2,3,1,2]
Output: 5
```

Source: [HackerRank](https://www.hackerrank.com/challenges/picking-numbers/problem)