# Algorithms (Cousera Computer Science: Algorithms, Theory, and Machines by Princeton University)
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
![Empirical_tests]()

### 1-3 Merge sort
Mergesort: divide the array in half, sort the two halves, merge the two halves to make a sorted whole.
<br>

Cost model: data moves: N = 2*N*lg*N*
