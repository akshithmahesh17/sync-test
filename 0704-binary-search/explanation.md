# Binary Search

**Problem:** #704
**Difficulty:** Easy
**Language:** Python3

## Algorithm

**Binary Search**

The student implemented the standard iterative Binary Search algorithm to find the index of a target value within a sorted list. It repeatedly divides the search interval in half by maintaining low and high pointers, comparing the middle element with the target, and adjusting the search range accordingly until the target is found or the range is exhausted.

## Step-by-step

1. Initialize two pointers, low at the beginning index 0 and high at the last index of the array.
2. Enter a while loop that continues as long as low is less than or equal to high.
3. Calculate the middle index mid to avoid potential integer overflow.
4. Check if the element at nums[mid] is equal to the target; if it is, return mid immediately.
5. If the target is less than nums[mid], update the high pointer to mid - 1 to search the left half.
6. If the target is greater than nums[mid], update the low pointer to mid + 1 to search the right half.
7. If the loop terminates without finding the target, return -1.

## Time Complexity

**O(log n)**

## Space Complexity

**O(1)**

## Key Concept

Divide and Conquer
