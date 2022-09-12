# The Drunkard's Walk 🟠

![A drunkard’s walk](https://miro.medium.com/max/1400/0*WJVuFrA0dhjH_ngR)

> \- Image from: https://medium.com/@mooneyse/a-drunkards-walk-20bbb6045522

A drunken sailor returns to his ship via a bridge `70 metre long` and `14 metre wide`.
What is the probability that he returns safely to his ship, considering:

**The Bridge:**

- Length (x direction) = 70 m
- Width (y direction) = 14 m

**The drunk has a:**

- 50% chance to step forward (x direction)
- 25% chance to step left (positive y direction)
- 25% chance to step right (negative y direction)
- Step length: 70 cm

**Boundary conditions:**

- Sailor's starting x position: 0
- Sailor's starting y position: Width/2
- open y boundaries (the sailor may fall off the bridge)

> Write a function that works as a single step simulator.
> Then, write another function (walk simulator) that calls the single step
> simulator several times to simulate an entire Sailor's trajectory, which
> can end with the sailor falling into the `water` or reaching the `ship`.
> Finally, write a probability function that calls the walk simulator several
> times to determine the approximate probability that the sailor will arrive
> on the ship.

## Rules

### Step simulator

1. Function returns a `string` value between `forward`, `left` and `right`.
2. Step is not "fair":
   - 50% `forward`
   - 25% `left`
   - 25% `right`
3. You can use any `random function` from the [`random` module](https://docs.python.org/3/library/random.html).

### Walk simulator

1. Function returns a `string` value between `water` and `ship`.
2. You should call the `step_simulator()` function.

### Probability calculator

1. Function returns a `float` value between `0` and `1`.
2. Avoid using any knowledge of combinatorics to solve this problem. Instead, take advantage of the fact that the machine can simulate millions of steps/walks in a very short time.

:::{note}
Since this is based on random draws, the probability will be slightly different
each time the code is run.

<!-- ## Useful Links

- [Python Strings](https://www.w3schools.com/python/python_strings.asp)
- [Python String Methods](https://www.w3schools.com/python/python_strings_methods.asp)
  - Specially: `isdigit()`, `islower()`, `isupper()`, `join()`
- [Python - Modify Strings](https://www.w3schools.com/python/python_strings_modify.asp)
- [Python Built in Functions](https://www.w3schools.com/python/python_ref_functions.asp)
  - Specially: `all()`, `any()`, `len()` -->
