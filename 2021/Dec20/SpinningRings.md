# Spinning Rings

Imagine two rings with numbers on them. The inner ring spins clockwise and the outer ring spins anti-clockwise. We start with both rings aligned on 0 at the top, and on each move we spin each ring by 1. How many moves will it take before both rings show the same number at the top again?

The inner ring has integers from 0 to innerMax and the outer ring has integers from 0 to outerMax, where innerMax and outerMax are integers >= 1.

Example 1:
```
e.g. if innerMax is 2 and outerMax is 3 then after
1 move: inner = 2, outer = 1
2 moves: inner = 1, outer = 2
3 moves: inner = 0, outer = 3
4 moves: inner = 2, outer = 0
5 moves: inner = 1, outer = 1
Therefore it takes 5 moves for the two rings to reach the same number
Therefore spinningRings(2, 3) = 5
```

Example 2:
```
e.g. if innerMax is 3 and outerMax is 2 then after
1 move: inner = 3, outer = 1
2 moves: inner = 2, outer = 2
Therefore it takes 2 moves for the two rings to reach the same number
spinningRings(3, 2) = 2
```

<i>Optimize your solution for better performance!</i>

Source: [Code Wars](https://www.codewars.com/kata/59b0b7cd2a00d219ab0000c5)