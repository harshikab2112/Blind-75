## Heap Problems  
The **Heap** topic focuses on problems that involve using heap data structures, which are useful for efficiently solving problems related to ordering, priority, and selection.

### Problems:  
1. **Merge K Sorted Linked Lists**  
   Merge `K` sorted linked lists into one sorted linked list using a min-heap (priority queue).  
2. **Top K Frequent in Array**  
   Find the `K` most frequent elements in an array using a max heap or min heap.  
3. **Find Median in a Stream**  
   Find the median of a stream of integers in real time by maintaining a balanced heap structure (usually using two heaps: a max-heap for the lower half and a min-heap for the upper half).

### Approach  
- For problems like merging `K` sorted lists, use a min-heap to efficiently select the smallest element from multiple lists.  
- For "Top K Frequent," use a heap to track the most frequent elements, optimizing for time complexity over brute force.  
- For dynamic median problems, maintain two heaps to efficiently get the median at any point in the stream.  
- Be aware of the heap's time complexity (`O(log n)` for insertion and deletion) and use it to optimize your solutions.
