1. On the first problem you have used a randomised algorithm to find all
the vertices. This is obviously highly inefficient. Instead this could
have been done with very simple code like:

```
V = [(i,j) for i in range(1, 5) for j in range(i+1, 6)]
```

2. The edge relations are complementary to those requested.

3. For the second graph, the vertices are all words summing to an integer
less than or equal to 10.

*Score 1/10*
