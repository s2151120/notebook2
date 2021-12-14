# Subspaces and Eigenvalues
#ilasem1 
Created: 2021-11-10 07:10

Eigenvalues are defined to be some $\lambda \in \mathbb{R}$ where
$Ax = \lambda x$. Then $0 = (\lambda I-A)x$.

An **eigenspace** can be represented as $E_\lambda$ just like in [[Formalising the big-O notation.]] where we used function style notation to represent a set. 

The eigenspace of a vector is the list of vectors of which the eigenvalue of a vector is true:

$E_\lambda (A) = \{x \in \mathbb{R}^n | Ax = \lambda x\}$

Then a vector $x$ is in $E_\lambda(A)$ iff $(\lambda I - A)x = 0$

This takes the form of [[Null space]]

>null $A = \{x \in \mathbb{R}^n | Ax = 0\}$

Where the $A$ in null $A$ is represents $(\lambda I - A)$. Therefore null ($(\lambda I - A)x = 0$) is a valid subspace of $\mathbb{R}^n$.

[[Spanning sets]]

## References
1. 