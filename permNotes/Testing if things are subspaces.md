# Testing if things are subspaces
#ilasem1 
Created: 2021-11-10 06:25

From the example in [[Writing equations in set theory notation.]] we said that $M = \{v \in \mathbb{R}^3 | n  \cdot v = 0\}$.

We need to test if $M$ is a subspace of $\mathbb{R}^3$.

Referring to the rules we set [[Defintion of Subspace of R^n]] we know that

>1. The zero vector $0$ $\in$ $U$.
2. If $x \in U$ and $y \in U$, then $x+y \in U$
3. If $x \in U$ then $ax \in U$ for every real number a.

Testing for the first condition:
Let $v = 0$ then
$n \cdot 0 = 0$ which is automatically true. Therefore first condition holds.

Then thinking about the second condition:
Let $x = \begin{bmatrix} x_1 \\ x_2 \\ x_3\end{bmatrix}$

and $y = \begin{bmatrix} y_1 \\ y_2 \\ y_3\end{bmatrix}$

Then if $x \in U$ is true: $n \cdot x = 0$

And if $y \in U$ is true: $n \cdot y = 0$

But then $(x+y) \cdot n = x \cdot n + y \cdot n$ due to[[ the distributive law of the dot product]]. Since we took $n /cdot y = 0$ and $x /cdot n = 0$ then $(x+y) \cdot n = 0$ which means $x+y \in U$ is true therefore second condition holds.

For the third condition:
$x \in U$ is true therefore $x \cdot n = 0$. When expanded out it gives the equation:

$x_1 \cdot a + x_2 \cdot b + x_3 \cdot = 0$

If we multiply by a real number $a \neq 0$ then $a(x_1 \cdot a + x_2 \cdot b + x_3 \cdot) = a \cdot 0 = 0$

Therefore the third condition holds.

Due to holding these three conditions, $M$ is in the subspace of $\mathbb{R}^3$.

## References
1. 