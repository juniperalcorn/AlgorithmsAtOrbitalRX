# Cat and Mouse

Two cats and a mouse are at various positions on a line. You will be given their starting positions. Your task is to determine which cat will reach the mouse first, assuming the mouse does not move and the cats travel at equal speed. If the cats arrive at the same time, the mouse will be allowed to move and it will escape while they fight.

Your input will be 3 integers, `A`, `B`, and `C`. `A` and `B` are the positions of the cats, `C` is the position of the mouse.

If cat  catches the mouse first, print Cat A.
If cat  catches the mouse first, print Cat B.
If both cats reach the mouse at the same time, print Mouse C as the two cats fight and mouse escapes.

Example:
```
input: 12, 4, 13
output: Cat A

input: 21, 23, 22
output: Mouse C
```

Source: [HackerRank](https://www.hackerrank.com/challenges/cats-and-a-mouse/problem)