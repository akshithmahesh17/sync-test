# Palindrome Number

**Problem:** #9
**Difficulty:** Easy
**Language:** Python3

## Algorithm

**String Reversal**

The student converts the given integer into a string, reverses that string using Python's slicing feature, and then compares the original string with the reversed string to check if they are the same.

## Step-by-step

1. Convert the input integer x into its string representation and store it in a variable called original.
2. Reverse the string original using Python slicing ([::-1]) and store it in a variable called reversed.
3. Compare the original string and the reversed string.
4. Return True if they are identical, otherwise return False.

## Time Complexity

**O(N) where N is the number of digits in the integer, because converting the integer to a string and reversing it both take time proportional to the number of digits.**

## Space Complexity

**O(N) because storing the string representation of the integer and its reversed copy requires extra memory proportional to the number of digits.**

## Key Concept

Strings
