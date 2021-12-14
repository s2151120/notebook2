# Proof that null A and im A are valid subspaces
#ilasem1 
Created: 2021-11-10 06:44

Recalling conditions for subspaces:

[[Defintion of Subspace of R^n]]

>1. The zero vector $0$ $\in$ $U$.
2. If $x \in U$ and $y \in U$, then $x+y \in U$
3. If $x \in U$ then $ax \in U$ for every real number a.

We need to prove that null $A$ and im $A$ are valid subspaces of $\mathbb{R}^n$.

### null A

1. null $A$ = $Ax = 0$. $A0 = 0$ therefore the zero vector is inside nulln $A$.
2. $A(x_1 + x_2) = Ax_1 + Ax_2$ due to the distributive law of matrix multiplication. Since $Ax = 0$ and we are drawing $x$ from a set of valid solutions, $Ax_1 + Ax_2 = 0$ therefore closed addition holds.
3. $A(x) = 0$ then $R \cdot A(x) = R \cdot 0$ where $R$ is a real number. $R\cdot A(x) = 0$ therefore closed multiplication holds.

It follows that the null space of $A$ is a valid subspace in $\mathbb{R}^3$

### im A

im A is defined by [[Image space]]

>im $A = \{Ax | x \in \mathbb{R}^n\}$

Meaning $Ax = y$ where $x$ is a list of solutions.

1. $A(0) = 0$ and $0$ is in $\mathbb{R}^n$ therefore the image subspace contains the zero vecor.
2. $A(x_1 + x_2) = A(x_1) + A(x_2) = y_1 + y_2$ Since both of these are solutions, we can say that $A(x_1), A(x_2) \in$ im $A$ therefore addition is closed.
3. $R \cdot A(x) = Ry$ then $A(rx) = Ry$ which means multiplication is closed.

It follows that the image-space of A is a valid subspace in $\mathbb{R}^3$.

[[Subspaces and Eigenvalues]]

Looking at a set that isn't a valid subspace: [[Invalid subsets]]

## References 
1. 