# Snake Cube Solution

The snake cube is a puzzle consisting of 27 small wooden cubes connected by an elastic string.

The challenge is the twist the string of cubes into a complete 3 x 3 x 3 cube.

Some of the small cubes are threaded straight through the centre. Others are threaded at a right-angle - this allows the solver to change direction.

![Image of cube]
(../Diaggrams/snake1.png)

![Image of Flattened Cube]
(../Diagrams/snake02.png)


We describe the configuration of the puzzle by a list of 0s and 1s where:

0 means a cube which is threaded straight through (or is at either end of the string).
1 means a cube which is threaded at right angles.

In the tests, all configurations will be of length 27, and consist only of 0s and 1s.

We describe a solution as Just a list of 3D cartesian coordinates, Maybe [(Int, Int, Int)] describing the position of each cube within the final 3 x 3 x 3 cube.

Your task is to produce a valid solution for a given starting configuration. If there are multiple solutions then return any one. If there is no possible solution then return Nothing.

For the purposes of this kata, the complete solution occupies a cube with vertices:

(0,0,0) (2,0,0) (0,2,0) (0,0,2) (2,2,0) (2,0,2) (0,2,2) (2,2,2)

and starts with the first cube in the corner position (0,0,0).



Source: (Codewars)[https://www.codewars.com/kata/5df653efc6ba5100191e602f]