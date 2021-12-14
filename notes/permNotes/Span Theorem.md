# Span Theorem
#ilasem1 
Created: 2021-11-10 08:16

### Formal definition: 

Let $U$ = span $\{x_1, x_2, \cdots, x_k\}$ in $\mathbb{R}^n$. Then:

1. $U$ is a subspace of $\mathbb{R}^n$ containing each $x_i$
2. If $W$ is a subspace of $R^n$ and each $x_i \in W$ then $U \subseteq W$.

### Making sense of it in words:

Basically, it's saying that if we take U to be a set of linear combinations of $\{x_1, x_2, \cdots, x_k\}$, in other words the [[Span]], we find that U is a subspace in n-dimension and contains all of its composite vectors. If there is some other subspace W and every vector of U is inside W then U is a subset of W. It's like a box within a box!

![boxWithinABox](https://m.media-amazon.com/images/I/91TWKY5WXhL._AC_SX679_.jpg)

[[Defintion of Subspace of R^n]]

### Formal proof:

We break it into two parts:

#### Part 1: Proving that $U$ is a subspace of $\mathbb{R}^n$ containing each $x_i$:

>1. The zero vector $0$ $\in$ $U$.
2. If $x \in U$ and $y \in U$, then $x+y \in U$
3. If $x \in U$ then $ax \in U$ for every real number a.

If $U$ is the span of k-vectors then:

$U = a_1x_1 + a_2x_2 + \cdots + a_kx_k$

1. Passing the zero vector through $U$ we get:
$U = 0$ which is in $U$ because zero is a valid linear combination.
2. $U_1 = a_1x_1 + a_2x_2 + \cdots + a_kx_k$ and $U_2 = b_1x_1 + b_2x_2 + \cdots + b_kx_k$ Then $U_1 + U_2 = a_1x_1 + b_1x_1 + a_2x_2 + b_2x_2 + \cdots + a_kx_k + b_kx_k$ Which can be sorted to a linear combination form: $U_1 + U_2 = (a_1 + b_1)x_1 + (a_2 + b_2)x_2 + \cdots + (a_k + b_k)x_k$ which is in $U$.
3. $U_1 = a_1x_1 + a_2x_2 + \cdots + a_kx_k$ So then $kU_1 = ka_1x_1 + ka_2x_2 + \cdots + ka_kx_k$ which is in $U$

Every $x_i$ in $U$ because ...

### Part 2: Proving that if W is a subspace of R and each vector of U is in W then U is a subspace of W.

$x = t_1x_1 + t_2x_2 + \cdots + t_kx_k$ where $x_i \in W$. Then each $t_ix_i \in W$ due to the closed multiplication rule. Since closed multiplication is true as well, $x_1t_1 + x_2t_2$ is in W, $x_1t_1 + x_2t_2 + x_3t_3$ is in W etc. So if all $x_it_i$ are in $W$ and all $x_it_i$ can be added together to produce a new term within the subspace then all $x_1t_1 + x_2t_2 + \cdots + x_kt_k = U$ is in $W$.

## References
1. 289, Application to Linear Algebra