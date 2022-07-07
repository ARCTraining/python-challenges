# Disarium Number 🟡

[A number is called **Disarium** if sum of its digits powered with their respective positions is equal to the number itself.](https://www.geeksforgeeks.org/disarium-number/#:~:text=A%20number%20is%20called%20Disarium,equal%20to%20the%20number%20itself.)

Examples:

| Number | Operation             | Is Disarium? |
| ------ | --------------------- | ------------ |
| 80     | 8^1 + 0^2 = 8         | False        |
| 89     | 8^1+9^2 = 89          | True         |
| 135    | 1^1 + 3^2 + 5^3 = 135 | True         |

Write a function that determines whether a number is a Disarium (True) or not (False).

:::{tip}
Combining `enumerate()` and `List Comprehension` it is possible to solve this problem in just 1 line!
:::

## Useful concepts

### Python’s `enumerate()`

Imagine that you have a list of colours, like:

```python
colours = ['blue', 'red', 'green']
```

You can use a loop structure to iterate over each item. For example, to print every colour:

```python
for colour in colours:
    print(colour)
```

the output:

```bash
blue
red
green
```

Now imagine that for each item you also need print the item position, we could do something like:

```python
i = 1
for colour in colours:
    print(colour, i)
    i = i + 1
```

that would result in

```bash
blue, 1
red, 2
green, 3
```

`enumerate()` can solve this problem easily: when you use `enumerate()`, the function gives you back two loop variables:

- The count of the current iteration
- The value of the item at the current iteration

Using the example above, we could write:

```python
for i, colour in enumerate(colours, start=1):
    print(colour, i)
```

to produce the output:

```bash
blue, 1
red, 2
green, 3
```

## Useful Links

- [Disarium Number](https://www.geeksforgeeks.org/disarium-number/#:~:text=A%20number%20is%20called%20Disarium,equal%20to%20the%20number%20itself.)
- [Built-in Functions: enumerate](https://docs.python.org/3/library/functions.html#enumerate)
- [List](https://docs.python.org/3/tutorial/datastructures.html)
- [List Comprehension](https://www.w3schools.com/python/python_lists_comprehension.asp)
- [Python operators](https://www.w3schools.com/python/python_operators.asp)
- [If statements & Conditionals](https://www.w3schools.com/python/python_conditions.asp)
- [Functions](https://www.w3schools.com/python/python_functions.asp)

## Content

```{tableofcontents}
```
