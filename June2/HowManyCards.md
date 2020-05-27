# How Many Cards?

Say you have a set of two-sided cards: each card has a drink on one side, and an age on the other. The cards have been mixed up and you can only see one side of each card. You have to make sure that no one under the drinking age is drinking an alcoholic drink. How many cards do you have to flip over?

```
Input:
alcoholicDrinks: a list of strings
drinkingAge: an integer
cards: an unsorted list of strings and integers.

Output: the number of cards that must be flipped, as an integer
```


Example:
```
alcoholicDrinks = ["VODKA", "GIN", "RUM", "BEER", "TEQUILA"]
drinkingAge = 21
cards = ["VODKA", 35, "COKE", 19, "BEER"]

Output: 3 ("VODKA", 19, and "BEER" all need to be flipped over)
```

Source: [Candidate Planet](https://www.youtube.com/watch?v=JbPY__PTBQY)