# Max Sum: Trees

You are given a binary tree. Implement the method maxSum which returns the maximal sum of a route from root to leaf. For example, given the following tree:
```
    17
   /  \
  3   -10
 /    /  \
2    16   1
         /
        13
```
The method should return 23, since [17,-10,16] is the route from root to leaf with the maximal sum.

You will want to implement a TreeNode class/func, this one is in JS but the logic is not language specific:
```
var TreeNode = function(value, left, right) {
  this.value = value;
  this.left = left;
  this.right = right;
};
```

Source: [Codewars](https://www.codewars.com/kata/57e5279b7cf1aea5cf000359)