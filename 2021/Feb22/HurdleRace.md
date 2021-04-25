# Hurdle Race

A video player plays a game in which the character competes in a hurdle race. 
Hurdles are of varying heights, and the characters have a maximum height they can jump. 
There is a magic potion they can take that will increase their maximum jump height by 1 unit for each dose. 
How many doses of the potion must the character take to be able to jump all of the hurdles? If the character can already clear all of the hurdles, return 0. Else, return the number of doses the character must take to complete the race.

Input
The first line contains two space-separated integers n and h, the number of hurdles and the maximum height the character can jump naturally.
The second line contains a list of the heights of the hurdles in the race. They are all integers greater than 0.

Examples:
```
Inputs:
5 4
[1, 6, 3, 5, 2]
Output: 2


Inputs:
5 7
[2, 5, 4, 5, 2]
Output: 0
```

Source: [HackerRank](https://www.hackerrank.com/challenges/the-hurdle-race/problem)