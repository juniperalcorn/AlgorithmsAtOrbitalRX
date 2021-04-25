# Count inversions in an array

Inversion Count for an array indicates – how far (or close) the array is from being sorted. If array is already sorted then inversion count is 0. If array is sorted in reverse order that inversion count is the maximum.

Formally speaking, two elements `a[i] and a[j]` form an inversion if `a[i] > a[j]` and `i < j`. If `a[i] < a[j]`, it is already sorted and it is not an inversion. `a[i]` has up to `n-1` possible inversions, with `n` being the length of the array.

Examples
```
Input: arr[] = {8, 4, 2, 1}
Output: 6

Explanation: Given array has six inversions:
(8,4), (4,2),(8,2), (8,1), (4,1), (2,1).


Input: arr[] = {3, 1, 2}
Output: 2

Explanation: Given array has two inversions:
(3, 1), (3, 2) 

Input: arr[] = {1, 2, 3}
Output: 0

Explanation: Given array has zero inversions (it has already been sorted)
```

Source: [GeeksForGeeks](https://www.geeksforgeeks.org/counting-inversions/)