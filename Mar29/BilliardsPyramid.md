# Billiards Pyramid

Remember the triangle of balls in billiards? To build a classic triangle (5 levels) you need 15 balls. With 3 balls you can build a 2-level triangle, etc.

<i>Illustration</i>
![Image of billiards pyramic](/Diagrams/billiards.png)

Write a function that takes a number <i>n</i>, and returns the number of full levels in a billiards pyramid you could make with <i>n</i> billiard balls.

The input will always be a whole, positive integer. Your output should also always be a whole, positive integer.

Examples:
```
pyramid(1) == 1

pyramid(3) == 2

pyramid(6) == 3

pyramid(10) == 4

pyramid(15) == 5
```

Source: [CodeWars](https://www.codewars.com/kata/5bb3e299484fcd5dbb002912)