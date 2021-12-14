# Data Representation
#icomsem1
Created: 2021-11-03 04:17

Why you should pay attention to data representation:
Time and resource consumption of code. 

### Rate of Growth: big-O notation

Consider a function `elem` that takes an integer A and compares it with list (A, B C) to see the first occurrence of A. In order to do so, it must go through every single element in the list until it hits the first instance of A. A can have an index of 0, 1 or 2 but the worst-case scenario would be if A had an index of 2. For example, the list (C, B, A) or (B, C, A) are the worst case scenarios for this situation. 

For the function `elem` which looks at a list of n-size and looks for some integer X, the time taken is $an + b$, where $a$ = time taken to check one item on the list and $b$ = the time taken to start the computation.

Since $a$ and $b$ are constants that vary from machine to machine, we can simplify and say that the worst-case run time of `elem` is $O(n)$. 

Like how $f(x)$ can be interpreted as a $y = x$ graph, we can interpret $O(n)$ to be a $y = n$ graph to get this shape:

![](https://qph.fs.quoracdn.net/main-qimg-9af0710089dddf436c615c748d51d894)

Meaning that the worst-case runtime can be described **linearly**.

[[Formalising the big-O notation.]]

[[Deciding which big-O notation to use.]]

[[Looking at quadratic time functions]]

[[Representing sets as lists]]

## References
1. Chapter 20, see [[Computational Logic]]