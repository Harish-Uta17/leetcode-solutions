# 1752. Check if Array Is Sorted and Rotated

**Difficulty:** Easy  
**LeetCode:** [Link to Problem](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/)

---

## Problem
Given an array `nums`, return `true` if the array was originally sorted in **non-decreasing order**, then **rotated** some number of positions (including zero). Otherwise, return `false`.

- A sorted array is rotated if it can be obtained by shifting some prefix of the array to the end.
- Example: `[0,1,2,4,5,6,7]` rotated at index 3 → `[4,5,6,7,0,1,2]`.

---

## Approach
- Traverse the array and count the number of places where `nums[i] > nums[(i+1) % n]`.
- If the count is more than `1`, the array cannot be sorted and rotated.
- If the count is `0` or `1`, return `true`.

---

## Complexity
- **Time:** O(n)  
- **Space:** O(1)

---

## Code
See [`1752_Check_if_Array_Is_Sorted_and_Rotated.cpp`](1752_Check_if_Array_Is_Sorted_and_Rotated.cpp)

---

## Example
Input:
