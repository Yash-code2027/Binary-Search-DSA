# Binary Search

## Problem

Search for a target element in a sorted array using Binary Search.

## Example

Array:
[2, 4, 6, 8, 10, 12]

Target:
8

Output:
3

## Approach

1. Set `low` to the first index.
2. Set `high` to the last index.
3. Find the middle index.
4. Compare `arr[mid]` with the target.
5. If equal, return the index.
6. If target is greater, search the right half.
7. Otherwise, search the left half.
8. Continue until the element is found or the search range becomes empty.

## Complexity

- Time: O(log n)
- Space: O(1)

## Key Learning

Binary Search works on a **sorted array** and reduces the search space by half at every step.