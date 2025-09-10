# 26. Remove Duplicates from Sorted Array

**Difficulty:** Easy  
**LeetCode:** [Link to Problem](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)

---

## Problem
Given an integer array `nums` sorted in non-decreasing order, remove the duplicates **in-place** such that each unique element appears only once. The relative order of the elements should be kept the same.  

Since it is impossible to change the length of the array in some languages, you must instead place the result in the first part of the array `nums`.  

Return the number of unique elements in `nums`.

---

## Approach
- Use the **two-pointer technique**:
  1. Keep one pointer `j` for the position of the last unique element.
  2. Iterate with pointer `i`.
  3. Whenever `nums[i] != nums[j]`, increment `j` and update `nums[j] = nums[i]`.
- Finally, the length of the unique array is `j + 1`.

---

## Complexity
- **Time:** O(n)  
- **Space:** O(1)

---

## Code
See [`26_Remove_Duplicates_from_Sorted_Array.cpp`](26_Remove_Duplicates_from_Sorted_Array.cpp)

---

## Example
Input:
