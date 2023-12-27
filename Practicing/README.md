# Data Structures and Algorithms
## Measure Running Time

## Binary Search (Half-Interval Search)
#### An algorithm used to find a specific element located in a sorted array. It halves the number of elements to check with each iteration. 

Worst Case -> `0(log n)` -> No matching element in the array.
Average Case -> `0(log n)` -> The matching element is somewhere but not in the middle.
Best Case -> `0(1)` -> The matching element is in the middle of the array.

## Linear Search (Sequential Search)
#### An algorithm that checks every element in an array, starting from the leftmost element, and continues until the desired element is found. 

Worst case -> `0(n)` -> No matching element in an array.
Average case -> `0(n)` -> The matching element is in the middle of the array.
Best case -> `0(1)` -> The element is in the first slot of the array.