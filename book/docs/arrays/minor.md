# Minor of Matrix

> Write a function that returns the Minor of Matrix of a 3x3 Matrix for a given
> line $(i)$ and column $(j)$

## Rules

1. Function returns a Numpy ndarray of shape=2x2
2. Function should work for all possible $i,j$ combination

## Useful Links

- [NumPy Array](https://numpy.org/doc/stable/reference/generated/numpy.array.html)
- [Indexing Methods](https://numpy.org/doc/stable/reference/arrays.indexing.html)
  - Specially: `ix_()`
- [NumPy Broadcasting](https://numpy.org/devdocs/user/basics.broadcasting.html)

## Minor of Matrix: Definition

> Minor of matrix for a particular element in the matrix is defined as the
> matrix obtained after deleting the row and column of the matrix in which that
> particular element lies.
> 
> \- [cuemath](https://www.cuemath.com/algebra/minor-of-matrix/)

![Minor of Matrix Example](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/minor-of-matrix-1626687634.png)

### Example

For example, consider the following 3x3 square matrix A:

$$
A = \begin{bmatrix}
9 & 12 & 18 \\
2 & -2 & 5 \\
11 & -17 & 19 
\end{bmatrix}
$$

The Minor of Matrix for the line $i=1$ and column $j=1$ is:

$$
M_{11} = \begin{bmatrix}
-2 & 5 \\
-17 & 19 
\end{bmatrix}
$$

and the Minor of Matrix for the line $i=2$ and column $j=3$ is:

$$
M_{23} = \begin{bmatrix}
9 & 12 \\
11 & -17 
\end{bmatrix}
$$

## Index Notation

Please note that in Matrix, the index starts with `1`. So, first line is index `1`.
On the other hand, indexing in python starts at `zero`, so, first line is index `0`.

Please remember to add some index "conversion" to ensure that you access the
desired index!

## Disclaimer

The definition of Minor of Matrix **is not** exactly the one presented above.
The Minor of Matrix is the determinant of the $M_{ij}$ matrix.
But for the sanity of this challenge, let's stop a step earlier and just get
the Matrix $M_{ij}$ itself.