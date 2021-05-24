# What color is the chessboard square?

You are given `coordinates`, a string that represents the coordinates of a square of the chessboard. Below is a chessboard for your reference.

![Chessboard image](/Diagrams/chessboard.png)

Return `true` if the square is white, and `false` if the square is black.

The coordinate will always represent a valid chessboard square. The coordinate will always have the letter first, and the number second.

Examples:
```
Input: coordinates = "a1"
Output: false
Explanation: From the chessboard above, the square with coordinates "a1" is black, so return false.

Input: coordinates = "h3"
Output: true
Explanation: From the chessboard above, the square with coordinates "h3" is white, so return true.

Input: coordinates = "c7"
Output: false
```

Source: [Leet Code](https://leetcode.com/problems/determine-color-of-a-chessboard-square/)