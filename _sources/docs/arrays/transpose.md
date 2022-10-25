# Matrix Transpose  🟠

> Write functions that return the transpose of a matrix A.

## Rules

1. Function returns an numpy array.
2. You must not use any external function to calculate the transpose.
3. Function should work for square and non-square matrix.

## Useful Links

- [Transpose](https://en.wikipedia.org/wiki/Transpose)

## Transpose overview

Consider a matrix $A$ of order $j\times i$. The transpose of a matrix $A$, denoted by $A^T$, may be constructed by writing the columns of $A$ as the rows of $A^T$.

Formally, in the i-th row, j-th column element of $A^T$ is the j-th row, i-th column element of $A$:

$$ [A^T]_{i, j} = A_{j,i}$$


### Example

Consider the following matrix $A$:

$$
A = \begin{bmatrix}
1 & 2 & 3\\
4 & 5 & 6
\end{bmatrix}
$$

The transpose is:

$$
A^T = \begin{bmatrix}
1 & 4\\
2 & 5 \\
3 & 6
\end{bmatrix}
$$
