
A commutative [[Ring]] is called *noetherian*, if it satisfies the ascending chain condition: 
Every increasing sequence $I_1\subseteq I_2\subseteq \dots$ of [[Ideal]]s becomes stationary, i.e. there is some $n$ with $I_{n} = I_{n+1} = \dots$ 

Noetherian Rings have the following properties:

* For a noetherian ring $R$, the [[Polynomial Ring]] $R[X_1,\dots,X_n]$  is also noetherian (Hilbert's Basis Theorem)
* If $R$ is noetherian and $I$ is an ideal, then $R/I$ is also noetherian.
* A noetherian ring $R$ is a UFD ([[Factorial Ring]]) iff every prime ideal of height $1$ is principal,

### Krull's Hauptidealsatz

Let $R$ be a noetherian ring and $f\in R$ be not a zero divisor and not a unit.
Then every minimal [[Prime Ideal]] containing $f$ has height 1.
