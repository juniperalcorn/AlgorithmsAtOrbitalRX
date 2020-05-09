# Sort case sensitive strings

Given a list of strings, return the alphabetized list. Strings are case-sensitive. If two strings are identical except for case, the capitalized string should be returned first.

Example:
```
Input: ["foo", "buzz", "baz", "bar", "Buzz"]
Output: ["bar", "baz", "Buzz", "buzz", "foo"]
```

Notes: for two strings that are identical except for case, only check the first letter to decide which should be returned first.
Example:
```
Input: ["buzz", "Buzz", "buZZ"]
```
"Buzz" should be returned first, but either of the remaining strings can follow.