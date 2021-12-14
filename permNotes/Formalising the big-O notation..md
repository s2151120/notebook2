# Formalising the big-O notation.
#icomsem1 
Created: 2021-11-04 02:37

Simply, big-O notation describes a set of functions that obey a certain condition. 

Let $f(x)$ and $g(x)$ be functions that map like this: $\{ \mathbb{N} \rightarrow \mathbb{R}, y \geq 0\}$

Then $f(x) = O(g(x))$, that is $f(x)$ belongs in a superset $O(g(x))$, iff $f(m) \leq cg(m)$ for all $x \geq m$ where c is some scalar value.

In the case of the graph below, where $f(x) = x$ and $g(x) = x^2$, $x = 1$ is the point at which $f(x) \leq g(x)$ providing we don't count $0$ as a positive integer as input. Because $f(x)$ meets this condition when analysing its positive quadrant, we say that $f(x) = O(g(x))$ is true. In other words $f(x)$ is in the superset $O(g(x))$.

![[g and f graph.png]]
## References
1. https://en.wikipedia.org/wiki/Big_O_notation