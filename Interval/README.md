## Interval Problems  
The **Interval** topic focuses on problems involving ranges, overlaps, and sorting intervals. These problems will help you develop skills in efficiently handling interval-based operations.

### Problems:  
1. **Insert Interval**  
   Insert a new interval into a sorted list of intervals and merge if necessary.  
2. **Overlapping Intervals**  
   Merge all overlapping intervals in a given list of intervals.  
3. **Non-overlapping Intervals**  
   Find the minimum number of intervals to remove so that the remaining intervals are non-overlapping.  
4. **Meeting Rooms**  
   Determine if a person can attend all meetings given their start and end times.  
5. **Meeting Rooms II**  
   Find the minimum number of meeting rooms required to accommodate all meetings without conflicts.  

### Approach  
- Start by sorting intervals based on their start or end times, depending on the problem.  
- Use techniques like two-pointer traversal, heap (priority queue), or greedy algorithms for efficient solutions.  
- Pay attention to edge cases such as overlapping at boundaries or empty input lists.  
- Focus on time complexity, particularly for sorting-based solutions which are typically `O(n log n)`.  
