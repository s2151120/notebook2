# Invalid subsets
#ilasem1 
Created: 2021-11-10 07:22

Determining whether $U_1 = \{[x, y] | x \geq 0\}$ is a subset of $\mathbb{R}^2$.

Considering the definition of a subspace:
[[Defintion of Subspace of R^n]]

>1. The zero vector $0$ $\in$ $U$.
2. If $x \in U$ and $y \in U$, then $x+y \in U$
3. If $x \in U$ then $ax \in U$ for every real number a.

We can work our way down the conditionals:

1. Is the zero vector contained in $U_1$? When $x, y = 0$ then $x \geq 0$ so condition 1 is true.
2. Let's say $x_1 \geq 0$ and $x_2 \geq 0$ then $x_1 + x_2 \geq 0$ so this condition is true.
3. Let's say $x \geq 0$. We multiply by some constant $k$ to get $kx$. Since the only constraint on $k$ is to be real, $k$ can be negative meaning $kx \geq 0$ **is false as a general case**. Therefore multiplication is not closed.

$U_1$ is not a subspace of $\mathbb{R}^n$.

## References
1. 