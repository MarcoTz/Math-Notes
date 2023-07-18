Let $L$ be a [[Lattice]] and a $d$-dimensional lattice [[Polytope]] $P$ in $\mathbb{R}^n$ and let $L(P,t)$ be the number of lattice points contained in $tP$, where $tP$ is the polytope obtained by mutliplying each vertex of $P$ by $t$. 
Then we can write $L(P,t)=L_d(P)t^d+L_{d-1}(P)^{d-1}+\dots+L_0(P)$ for some [[Rational Numbers]] $L_0(P),\dots,L_d(P)$. 
If $P$ is closed and convex ([[Convexity]],[[Topological Space]]) the following formula holds: $L(int P,t)=(-1)^d L(P,-t)$.

### Erhard Series 

With these definitions, the *Erhard Series* of $P$ is the infinite power series $\sum_{t\geq 0} L(P,t)z^t$

### Properties
 
1. $L_d(P)$ is equal to the normalized volume of $P$, which is $d!$ times the volume of $P$
2. $L_0(P)$ is equal to the euler characteristic of $P$ ([[Euler Characteristic]])