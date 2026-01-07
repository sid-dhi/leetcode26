# LeetCode 26: Remove Duplicates from Sorted Array
Problem Description
Given an integer array nums sorted in non-decreasing order, remove duplicates in-place such that each unique element appears only once. The relative order of elements must be maintained. Return the number of unique elements.

How It Works
The algorithm uses two pointers:
Pointer k: Tracks the position where the next unique element should be placed
Pointer i: Iterates through the array to check each element
Since the array is already sorted, duplicates appear consecutively. The algorithm only keeps the first occurrence of each unique element by comparing each element with its predecessor.

Time Efficiency: Linear time complexity O(n)
Space Efficiency: Constant space complexity O(1)
Readability: Clear and intuitive two-pointer approach
Interview Friendly: Demonstrates understanding of in-place array manipulation

Complexity Analysis
Time Complexity: O(n) - Single pass through the array
Space Complexity: O(1) - In-place modification, no additional data structures used

EXAMPLE:
Input: nums = [0,0,1,1,1,2,2,3,3,4]
Output: 5, nums = [0,1,2,3,4,_,_,_,_,_]

