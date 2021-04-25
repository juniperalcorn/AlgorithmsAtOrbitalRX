# Middle Me

Write a function that will take a key of X and place it in the middle of Y repeated N times.

Rules:
If X cannot be placed in the middle, return X.
N will always be > 0.

Examples:
```
X = 'A';
Y = '*';
N = 10;

Y repeated N times = '**********';

X in the middle of Y repeated N times = '*****A*****';
Therefore output = '*****A*****';
```

```
X = 'abc';
Y = 'f';
N = 7;

Output: 'abc'
```

```
X = 'abc';
Y = 'f';
N = 6;

Y repeated N times = 'ffffff';

X in the middle of Y repeated N times = 'fffabcfff';
Therefore output = 'fffabcfff';
```


Extra challege: You can complete this with under 70 characters without using regex. 

Source: [CodeWars](https://www.codewars.com/kata/59cd155d1a68b70f8e000117)