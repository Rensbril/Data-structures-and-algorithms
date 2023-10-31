# Analyzing Algorithm Efficiency

As we develop algorithms, it's crucial to understand how their execution time scales with respect to the size of the input, denoted as `n`. This understanding is encapsulated by the Big O notation, which describes an algorithm's time complexity.

## Constant Time: `O(1)`

In constant time complexity, the algorithm's execution time remains constant, irrespective of the input size `n`. These algorithms are considered highly efficient.

**Examples**:

- Arrays:
- Hashmaps/sets

## Linear Time: `O(n)`

Linear time complexity indicates that the algorithm's execution time grows linearly as the input size `n` increases. This is often represented by the equation `y = x`.

**Examples**:
- Looping through an array.
- Inserting/removing elements in the middle of an array:
    - Insertion requires shifting all subsequent elements to make space for the new item.
- Searching within an array:
    - Potentially examining every item in the array.

## Quadratic Time: `O(n^2)`

Quadratic time complexity often arises from algorithms with nested loops, where the inner loop executes `n` times for each iteration of the outer loop.

**Examples**:
- Basic sorting algorithms like Bubble Sort or Selection Sort.
- Algorithms with nested loops processing `n` elements.

## Cubic Time and Beyond: `O(n^3), O(n^4), O(n^5), ...`

These complexities are less common and typically arise in algorithms with three or more nested loops.

## Logarithmic Time: `O(log n)`

Logarithmic time complexity algorithms significantly reduce the problem size (`n`) with each step, often by half. This is represented by the question: How many times can we halve `n` until we reach 1?

**Examples**:

- Binary search on a sorted array.
- Searching in a balanced binary search tree.
- Pushing and popping from a heap.

## Linearithmic Time: `O(n log n)`

Linearithmic time complexity combines linear and logarithmic characteristics, common in more efficient sorting algorithms.

**Examples**:

- Heapsort
- Mergesort

## Graph Complexity Analysis

![[Pasted image 20231024151819.png]]]
