# MinHeap

### Implemented a min-heap in Java and understood the core concepts of heaps.

### In summary:

### - Min-heaps created using the MinHeap class track the minimum element by storing it in index 1 of an ArrayList.

### - When adding elements, we call .bubbleUp() to compare the new element with its parent, making swaps if it violates the heap condition (min-heap children MUST be greater than their parents!)
 
### - When removing the minimum element, we swap it with the last element in the heap. Then we use .heapify() to compare the new root value with its children, swapping with its smaller child if necessary down the heap.

### - Min-heaps are useful because they are efficient in maintaining the heap condition and keeping track of the minimum element in a dataset.