# Convert a Linked List To String

Create a function `stringify` which accepts an argument `list` and returns a string representation of the list. The string representation of the list starts with the value of the current Node, specified by its `data` property, followed by a whitespace character, an arrow and another whitespace character (" -> "), followed by the rest of the list. The end of the string representation of a list must always end with `null/NULL/None/nil/nullptr/null()` (all caps or all lowercase depending on the language). 

The Node class is available to you here:
```
class Node():
    def __init__(self, data, next = None):
        self.data = data
        self.next = next
```

Examples:
```
Input: Node(1, Node(2, Node(3)))
Output: "1 -> 2 -> 3 -> None"

Input: Node(0, Node(1, Node(4, Node(9, Node(16)))))
Output: "0 -> 1 -> 4 -> 9 -> 16 -> None"
```

Source: [CodeWars](https://www.codewars.com/kata/582c297e56373f0426000098)