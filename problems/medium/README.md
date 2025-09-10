# 189. Rotate Array

**Difficulty:** Medium  
**LeetCode:** [Link to Problem](https://leetcode.com/problems/rotate-array/)

---

## Problem
Given an integer array `nums`, rotate the array to the right by `k` steps, where `k` is non-negative.

---

## Approach
- Use the **reverse method**:
  1. Reverse the entire array.
  2. Reverse the first `k` elements.
  3. Reverse the remaining `n - k` elements.
- This ensures in-place rotation without extra space.

---

## Complexity
- **Time:** O(n)  
- **Space:** O(1)

---

## Code
See [`189_Rotate_Array.cpp`](189_Rotate_Array.cpp)

---

## Example
Input:
