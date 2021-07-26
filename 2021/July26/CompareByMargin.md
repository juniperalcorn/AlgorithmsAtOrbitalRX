# Compare By Margin

Create a function `close_compare` that accepts 3 parameters: `a`, `b`, and an optional `margin`. The function should return whether `a` is lower than, close to, or higher than `b`.

a is considered "close to" `b` if `margin` is greater than or equal to the distance between `a` and `b`.

Please note the following:

When `a` is close to `b`, return `0`.
Otherwise...

When `a` is less than `b`, return `-1`.

When `a` is greater than `b`, return `1`.

If `margin` is not given, treat it as zero.

Assume: `margin >= 0`

Examples:
```
a = 3
b = 5
margin = 3
close_compare(a, b, margin) = 0
```

```
a = 3
b = 5
margin = 0
close_compare(a, b, margin) = -1
```

Source: [CodeWars](https://www.codewars.com/kata/56453a12fcee9a6c4700009c)