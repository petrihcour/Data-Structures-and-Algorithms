# Data Structures and Algorithms

## Measure Running Time
Work in progress

## Binary Search (Half-Interval Search)
#### An algorithm used to find a specific element located in a sorted array. It halves the number of elements to check with each iteration. 

- Worst case -> `0(log n)` -> No matching element in the array.
- Average case -> `0(log n)` -> The matching element is somewhere but not in the middle.
- Best case -> `0(1)` -> The matching element is in the middle of the array.

## Bubble Sort (Sinking Sort)
#### A comparison sorting algorithm that repeatedly steps through the elements in an array, compares two adjacent elements, and swaps them if they are in the wrong order. The pass through the array repeats until the array is sorted. 

- Worst case -> `0(n^2)` -> Every element is out of order.
- Average case -> `0(n^2)` -> Some elements are out of order.
- Best case -> `0(n)` -> The list is already sorted.

## Linear Search (Sequential Search)
#### An algorithm that checks every element in an array, starting from the leftmost element, and continues until the desired element is found. 

- Worst case -> `0(n)` -> No matching element in an array.
- Average case -> `0(n)` -> The matching element is in the middle of the array.
- Best case -> `0(1)` -> The element is in the first slot of the array.