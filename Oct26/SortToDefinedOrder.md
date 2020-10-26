# Sort To Defined Order

Given two arrays, an unsorted array and a reference array, reorder the elements of the first array according to the order defined in the reference array. Return the first array, sorted.

If the unsorted array contains elements that are not in the reference array, append them to the sorted array in the order they appeared. Elements in the reference array do not necessarily need to appear in the unsorted array.

Examples: 
```
Input:
unsorted = [5, 8, 9, 3, 5, 7, 1, 3, 4, 9, 3, 5, 1, 8, 4]
reference = [3, 5, 7, 2]

Output: [3, 3, 3, 5, 5, 5, 7, 1, 1, 4, 4, 8, 8, 9, 9]

Input:
unsorted = ['f', 'm', 'l', 'o', 'm', 'g']
reference = ['o', 'm', 'l', 'g', 'e']

Output: ['o', 'm', 'm', 'l', 'g', 'f']
```

Source: [Techie Delight](https://www.techiedelight.com/custom-sort-sort-elements-array-order-elements-defined-second-array/)