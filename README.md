# Binary-Search-Algorithm

Binary Search is applied on the sorted array or list of large size. The only limitation is that the array or list of elements must be sorted for the binary search algorithm to work on it.

Time Complexity: O(log n)

Implementing Binary Search Algorithm
Following are the steps of implementation that we will be following:

Start with the middle element:
1. If the target value is equal to the middle element of the array, then return the index of the middle element.
    - If not, then compare the middle element with the target value,
    - If the target value is greater than the number in the middle index, then pick the elements to the right of the middle index, and start with Step 1.
    - If the target value is less than the number in the middle index, then pick the elements to the left of the middle index, and start with Step 1.
2. When a match is found, return the index of the element matched.
3. If no match is found, then return -1.

## Code for Binary Search
<img src="https://webrewrite.com/wp-content/uploads/2018/05/Screen-Shot-2018-05-27-at-12.26.53-PM.png" width="650" height="500">

Though its in java, but still uses the same process in other languages.
