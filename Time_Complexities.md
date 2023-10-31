
For an in depth explanation of the time complexities see [Analyzing Algorithm Efficiency](./Analyzing_Algorithm_Efficiency.md)

### Data Structures:

1. **Arrays**:
    - Access: O(1)
    - Search: O(n)
    - Insertion: O(n)
    - Deletion: O(n)

2. **Linked Lists**:
    - Access: O(n)
    - Search: O(n)
    - Insertion: O(1)
    - Deletion: O(1)

3. **Stacks/Queues**:
    - Access: O(n)
    - Search: O(n)
    - Insertion: O(1)
    - Deletion: O(1)

4. **Hash Tables**:
    - Access: O(1) average, O(n) worst
    - Search: O(1) average, O(n) worst
    - Insertion: O(1) average, O(n) worst
    - Deletion: O(1) average, O(n) worst

5. **Binary Trees**:
    - Access: O(log n) average, O(n) worst
    - Search: O(log n) average, O(n) worst
    - Insertion: O(log n) average, O(n) worst
    - Deletion: O(log n) average, O(n) worst

6. **Balanced Binary Search Trees (e.g., AVL, Red-Black Trees)**:
    - Access: O(log n)
    - Search: O(log n)
    - Insertion: O(log n)
    - Deletion: O(log n)

7. **Heaps (Binary Heap)**:
    - Access: O(1)
    - Search: O(n)
    - Insertion: O(log n)
    - Deletion: O(log n)

8. **Graphs** (represented with adjacency list):
    - Access: O(1)
    - Search: O(|V| + |E|) using BFS/DFS
    - Insertion: O(1)
    - Deletion: O(|E|)

### Algorithms:

1. **Sorting Algorithms**:
    - Bubble Sort: O(n^2)
    - Selection Sort: O(n^2)
    - Insertion Sort: O(n^2)
    - Merge Sort: O(n log n)
    - Quick Sort: O(n log n) average, O(n^2) worst
    - Heap Sort: O(n log n)

2. **Searching Algorithms**:
    - Linear Search: O(n)
    - Binary Search: O(log n)

3. **Graph Algorithms**:
    - Breadth-First Search (BFS): O(|V| + |E|)
    - Depth-First Search (DFS): O(|V| + |E|)
    - Dijkstra's Algorithm: O((|V| + |E|) log V)
    - Floyd-Warshall: O(|V|^3)

4. **Dynamic Programming**:
    - Most dynamic programming problems have a time complexity related to the size of the input and the "dimension" of the memoization table. Common complexities are O(n), O(n^2), or O(n^3), among others.

5. **Divide and Conquer Algorithms**:
    - Most divide and conquer algorithms, like Merge Sort and Quick Sort, have time complexities of O(n log n).

These complexities are under typical or average conditions, and actual performance may vary depending on the specifics of the implementation and the data involved.
