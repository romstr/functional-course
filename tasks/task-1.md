# Task 1
#### Calculator

Create a function calculator that would take a string and return a result or 0.
```
["1", "+", "1"] -> 2
["1", "-", "1"] -> 0
["2", "*", "3"] -> 6
["4", "/", "2"] -> 2
["1", "+", "30", "-", "2"] -> 29
["2", "-", "1", "*", "2", "+", "-1"] -> -1
```

- Optional: Add support for ()
- Optional: Use raw string as a parameter and implement parsing yourself `"2 - 1 * 2 + 1" -> 1`

As a first step parse Expression to a Syntax Tree
