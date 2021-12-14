# Deciding which big-O notation to use.
#icomsem1 
Created: 2021-11-04 03:37

The best big-O notation to use would be the function that gives you the slowest growing time. 

For example if you have determined that a function takes $2n$ seconds to return an input, $f(n) = 2n$ belongs in many $O(g(n))$ sets such as $O(n)$ and $O(n^2)$. However, we pick $O(n)$ to represent the big-O notation for $f$ because it is the slowest growing one (i.e the most efficient).

## References
1. 