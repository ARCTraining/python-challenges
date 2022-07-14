# Decimal to Binary 🟡

> Write a function that returns the binary value (as string) for a positive integer decimal number

- The `decimal` number system is a number system that represents a number with a base of 10 and uses 10 digits:
  - 0, 1, 2, 3, 4, 5, 6, 7, 8, and 9.
- The `binary` number system is a number system with base 2 in which numbers are represented only by two digits:
  - 0 and 1.

There are different methods of converting numbers from decimal to binary.
One possibility is successively divide the decimal number by 2 (until the quotient is zero) and use the remainders to build the binary number.

See the example bellow using the decimal number 30:

| Number | Integer division by 2 | Remainder |
| ------ | --------------------- | --------- |
| 30     | 15                    | 0         |
| 15     | 7                     | 1         |
| 7      | 3                     | 1         |
| 3      | 1                     | 1         |
| 1      | 0                     | 1         |

The binary number is written using the Remainders from downwards to upwards, in the above example: `11110`

See another example:

![Binary Example](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/decimal-to-binary-conversion-1623818593.png)

## Useful Links

- [Decimal and binary](https://www.cuemath.com/numbers/decimal-to-binary/)
- [Modulus operator](https://www.geeksforgeeks.org/what-is-a-modulo-operator-in-python/)
- [List](https://docs.python.org/3/tutorial/datastructures.html)
- [Python operators](https://www.w3schools.com/python/python_operators.asp)
- [If statements & Conditionals](https://www.w3schools.com/python/python_conditions.asp)
- [Functions](https://www.w3schools.com/python/python_functions.asp)

## Content

```{tableofcontents}
```
