# Array to Tree

You are given a non-null array of integers. Implement the method arrayToTree which creates a binary tree from its values in accordance to their order, while creating nodes by depth from left to right.

For example, given the array [17, 0, -4, 3, 15] you should create the following tree:
```
    17
   /  \
  0   -4
 / \
3   15 
```

You will want to implement a TreeNode class/func, this one is in JS but the logic is not language specific:
```
var TreeNode = function(value, left, right) {
  this.value = value;
  this.left = left;
  this.right = right;
};
```

Source: [Codewars](https://www.codewars.com/kata/57e5a6a67fbcc9ba900021cd)