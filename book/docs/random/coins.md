# Tossing Coins 🟡

> Write a function that works as a coin-flipper simulator.
> Then, write another function that returns the approximate probability of
> getting a certain result combination for `2` tosses (regardless of order).

## Rules

### Coin-flipper simulator

1. Coin type: 2 faces: `head` and `tail`.
2. Coin is fair: equal chance of flipping `head` or `tail`.
3. The function must return a `string` value corresponding to the tossed face (`head` or `tail`).
4. You can use any `random function` from the [`random` module](https://docs.python.org/3/library/random.html).

### Probability calculator

1. Function that accepts `two` `string` inputs corresponding to the desired tossed faces, where:
   - The first input is necessary;
   - If no second input is given, it should should default to an empty string.
2. Function returns a `float` value between `0` and `1`.
3. Avoid using any knowledge of combinatorics to solve this problem. Instead, take advantage of the fact that the machine can simulate millions of tosses (samples) in a very short time.

:::{note}
Since this is based on random draws, the probability will be slightly different
each time the code is run.

**So, the greater the number of samples, the more consistent the results.**
:::

## Example

### Head & Tail or Tail & Head

If you call `get_probability(head, tail)` or `get_probability(tail, head)`, this
means you want to know the probability of drawing a `head` and a `tail`
(regardless of order) when tossing two coins. The result should be `0.50`.

### Head & Head

If you call `get_probability(head, head)`, this means you want to know the
probability of drawing two `heads` when
tossing two coins. The result should be `0.25`.

### At least one Head

Finally, if you call `get_probability(head)`, this means you want to know the
probability of drawing at least one `head` when
tossing two coins. This includes `head+tail`, `tail+head` and `head+head`, so
the result should be `0.75`.

## Content

```{tableofcontents}
```
