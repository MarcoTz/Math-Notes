Let $X$ be a complete nonsingular curve ([[Completion of a Sheaf]],[[Singularities]],[[Curve (Scheme)]]) over an algebraically closed [[Field]] $k$ with [[Function Field]] $K$. 
Let $\Omega_X$  be the sheaf of differentials ([[Sheaf of relative differentials]]) on $X$ and for $P\in X$ denote the stalk of $\Omega_X$ at $P$ by $\Omega_P$, and let $\Omega_K$ be the [[Module]] of differentials of $K$ over $k$.
Then for $P\in X$ closed, there is a unique $k$-linear ([[Linear Map]]) $res_P:\Omega_K \rightarrow k$ satisfying the following 
* $res_P(\tau) = 0$ for $\tau \in \Omega_P$
* $res_P(f^ndf) = 0$ for $f\in K^*$ and $n\neq 1$ 
* $res_P(f^{-1}df) = \nu_P(F)$ where $\nu_P$ is the valuation associated to $P$ ([[Valuation Ring]])
$res_P$ is called the *residue map* at $P$.

Then for $\tau\in \Omega_K$ we have $\sum_{P\in X} res_P\tau = 0$