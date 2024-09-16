

**Selection Sort**
Selection Sort is a straightforward and intuitive sorting algorithm that operates by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion.

__Algorithm__: 
__Initialization:__
Start with the first element of the array (index i = 0).

__Find the Minimum Element:__
Set the current index (i) as the minimum index (min_index). Iterate through the remaining elements of the array (from index i + 1 to the end): If an element smaller than the current minimum element is found, update min_index to the index of this smaller element.

__Swap Elements:__ 
Swap the element at the current index (i) with the element at min_index.

__Move the Boundary:__
Move the boundary of the sorted portion one position to the right (increment i by 1).

__Repeat:__
Repeat steps 2 to 4 until the entire array is sorted. End: The array is now sorted.

**Characteristics:**
__Time Complexity:__ Best, Average, and Worst Case: O(n²), where n is the number of items to be sorted.

__Space Complexity:__ O(1) auxiliary space, since it sorts the array in place.

__Stability:__ Selection sort is not stable, meaning equal elements might not retain their original relative order.

__Adaptive:__ The algorithm does not adapt to the input data; it performs a fixed number of comparisons and swaps regardless of the initial order of elements.

__Advantages:__
Simplicity: Easy to implement and understand.
In-place Sorting: Does not require additional memory beyond the input array.
__Disadvantages:__
__Inefficiency for Large Data:__ The quadratic time complexity makes it inefficient for large lists compared to more advanced algorithms like QuickSort or MergeSort.


https://11anshika.github.io/Selection-Sort/
