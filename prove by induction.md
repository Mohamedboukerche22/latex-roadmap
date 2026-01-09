<div align="center">

**Student:Mohamed boukerche**

# Solution : prove of by induction 

  
$$
\sum_{r=1}^{n} \left[ r(r+1)\left(\frac{1}{2}\right)^{r-1} \right] = 16 - \left(\frac{1}{2}\right)^{n-1}(n^2 + 5n + 8)
$$

## checking the Base Case: $n = 1$ wich is $P(1)$
  $$
\sum_{r=1}^{1} \left[ r(r+1)\left(\frac{1}{2}\right)^{0} \right]  = 1(2)(1) = 2
$$

$$
16 - \left(\frac{1}{2}\right)^{0}(6 + 8) = 16 - (1)(14) =  2 
$$

### $P(1)$ is true 
## Inductive Hypothesis 
Assume that $P(n)$ is true for $n > 0$ .

We need to prove that $P(n+1)$ is true.

We must show that the sum up to $n+1$ equals:

$$
16 - \left(\frac{1}{2}\right)^{(n+1)-1}((n+1)^2 + 5(1+n) + 8)
$$

$$
16 - \left(\frac{1}{2}\right)^{n}(n^2 +1 + 2n + 5+5n+ 8) = 16-\left(\frac{1}{2}\right)^{n}(n^2+7n +14)
$$

$$
 \boxed{16-\left(\frac{1}{2}\right)^{n}(n^2+7n +14)}
$$

The sum to $(n+1)$ is the sum to $n$ plus the $(n+1)$-th term:

$$
 \sum_{r=1}^{n+1} \left[ r(r+1)\left(\frac{1}{2}\right)^{r-1} \right] = \sum_{r=1}^{n} \left[ r(r+1)\left(\frac{1}{2}\right)^{r-1} \right] + (n+1)(n+2)\left(\frac{1}{2}\right)^n

$$
and since we have 

  
$$
\sum_{r=1}^{n} \left[ r(r+1)\left(\frac{1}{2}\right)^{r-1} \right] = 16 - \left(\frac{1}{2}\right)^{n-1}(n^2 + 5n + 8)
$$

 then we'll find out that :

$$
\left(16 - 2\left(\frac{1}{2}\right)^{n}(n^2 + 5n + 8)\right)+
(n+1)(n+2)\left(\frac{1}{2}\right)^n
$$
$$

16 - \left(\frac{1}{2}\right)^{n}[2(n^2 + 5n + 8) -(n+1)(n+2) ]

\newline

16 - \left(\frac{1}{2}\right)^{n}[2n^2 + 10n + 16 -n^2 -3n - 2 ]
\newline
\boxed{16 - \left(\frac{1}{2}\right)^{n}(n^2 + 7n + 14)}

$$

This matches our target for $P(n+1)$.

so $P(n)$ is also true 

Since the base case $P(1)$ is true and $P(k) \implies P(k+1)$

by the Principle of Mathematical Induction

**the statement is true for all $n \in \mathbb{N}, n \geq 1$.**



</div>
Student : mohamed boukerche 

discord handle : `mohb0u`

