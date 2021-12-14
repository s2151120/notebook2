# Looking at quadratic time functions
#icomsem1 
Created: 2021-11-04 03:44

The following would have a big-O notation of $O(n^2)$

`subset :: Eq a => [a] -> [a] -> Bool`
`subset ms ns = and [elem m ns | m <- ms]`

The `subset` function uses the `elem` function inside. This means that for each `m` pulled from the list `ms`, that `m` is checked against the list `ns` for all instances of `m` in that list meaning it has to go through every element in list `ns`. 

So taking $n$ to be the length of list `ns` and $m$ to be length of `ms`, we can say $m$ = $cn$. We can eliminate constants and condense into big-O notation:

$O(n^2)$

## References
1. 