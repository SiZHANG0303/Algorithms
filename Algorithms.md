# Algorithms (Coursera Computer Science: Algorithms, Theory, and Machines by Princeton University)
## 1- Sorting and Searching
### 1-1 Binary search
* Keep the array in sorted order
* Examine the middle key
* If it matches, return its index
* If it is larger, search the half with lower indices
* If it is smaller, search the half with upper indices

![Math_analysis](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/Mathematical_analysis_of_binary_search.png)
![Empirical_tests](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/Empirical_tests_of_binary_search.png)
### 1-2 Insertion sort
* Move down through the array
* Each item *bubbles up* above the larger ones above it
* Everything above the current item is in order
* Everything below the current item is untouched
* Like bubble sort but not; simpler and faster

![Empirical_tests](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/Empirical_tests_of_insertion_sort.png)

### 1-3 Merge sort(by John von Neumann)
* Divide the array in half
* Sort the two halves
* Merge the two halves to make a sorted whole.

![Mergesort_analysis](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/Mergesort_analysis.png)
![Empirical_tests](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/Empirical_tests_of_mergesort.png)

### 1-4 Longest repeated substring

![suffix_string](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/LRS_suffix_string.png)
![Empirical_tests](https://raw.githubusercontent.com/SiZHANG0303/Algorithms/master/LRS_empirical_nanlysis.png)

### Summary
* Binary search: efficient algorithm to search a sorted array
* Mergesort: efficient algorithm to sort an array

## 2- Stack and Queue
* Stack: Last In First Out(push/pop)
* Queue: First In First Out(Enqueue/Dequeue)
