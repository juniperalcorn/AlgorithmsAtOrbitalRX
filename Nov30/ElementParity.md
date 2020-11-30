# Element Parity

You will be given an array of integers, wherein each element will have a single positive occurrence, and a single negative occurrence. Eg, `[1, -1]`. However, there will be one integer that is missing its match. Eg, `[1, -1, -2]`. You must find the integer that does not have a corresponding negative/positive occurrence. 

Note: it is possible that the one integer will nonetheless be repeated, eg: `[1, -1, -2, -2]`. `-2` is still the odd one out, as there is no `2` in the list.

Examples:
```
Input: [1, -1, 2, -2, 3]
Output: 3


Input: [-3, 1, 2, 3, -1, -4, -2] 
Output: -4


Input: [1, -1, 2, -2, 3, 3]
Output: 3
```

Source: [CodeWars](https://www.codewars.com/kata/5a092d9e46d843b9db000064)