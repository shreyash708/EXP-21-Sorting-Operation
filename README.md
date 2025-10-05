# Aim: To implement Sorting techniques in C++.

Experiment 21 A: Selection Sort

Experiment 21 B: Bubble Sort

Experiment 21 C: Quick Sort

# Theory : 

# Quick Sort :
Mechanism: A Divide and Conquer algorithm. It picks an element as a pivot and partitions the rest of the array into two sub-arrays according to whether they are less than or greater than the pivot. It then recursively sorts the sub-arrays.

Key Trait: It is considered one of the fastest comparison-based algorithms in practice due to its O(nlogn) average-case performance and good locality of reference (better cache performance).

# Bubble Sort : 
Mechanism: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The largest element "bubbles up" to its correct position in each pass.

Key Trait: It can stop early if an array is sorted (O(n) best case), but performs a high number of swaps.

# Selection Sort :
Mechanism: Divids the array into a sorted and an unsorted part. It repeatedly finds the minimum element from the unsorted part and swaps it with the first element of the unsorted section.


Key Trait: It performs the minimum number of swaps (O(n) swaps in all cases).

# Algoorithm :

# 21 A – Selection Sort

Start the program.

Input size and array.

For each index i, find smallest element in rest of array.

Swap smallest element with element at index i.

Repeat until sorted.

End program.

# 21 B – Bubble Sort

Start the program.

Input size and array.

For each pass, compare adjacent elements.

Swap if left element > right element.

Repeat passes until no swaps occur.

End program.

# 21 C – Quick Sort

Start the program.

Input size and array.

Select last element as pivot.

Partition array into elements < pivot and > pivot.

Recursively apply quick sort on partitions.

Combine results to form sorted array.

End program.

# Conclusion
Implemented Selection, Bubble, and Quick Sort.
Observed efficiency differences:
Selection & Bubble → Simple, but slow (O(n²)).
Quick Sort → Much faster on large inputs.
Sorting is essential for search optimization and data organization.

