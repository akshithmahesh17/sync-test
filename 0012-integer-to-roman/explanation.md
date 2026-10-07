# Integer to Roman

**Problem:** #12
**Difficulty:** Medium
**Language:** Python3

## Algorithm

**Greedy Algorithm**

The student implemented a greedy algorithm that iterates through a predefined list of integer values and their corresponding Roman symbols, starting from the largest value down to the smallest. For each value, it determines how many times that value fits into the remaining number using integer division, appends the corresponding Roman symbol repeated that many times to a list, and updates the remaining number with the remainder.

## Step-by-step

1. Initialize a list of tuples containing integer values and their Roman numeral symbols in descending order, along with an empty list for the result.
2. Loop through each value and symbol pair in the predefined list.
3. Check if the remaining number has reached zero; if so, break out of the loop early.
4. Use divmod to divide the remaining number by the current value to find how many times the symbol fits and what the new remainder is.
5. Multiply the Roman symbol by the count and append it to the result list.
6. After the loop finishes, join all the strings in the result list together and return the final Roman numeral string.

## Time Complexity

**O(1)**

## Space Complexity

**O(1)**

## Key Concept

Greedy approach
