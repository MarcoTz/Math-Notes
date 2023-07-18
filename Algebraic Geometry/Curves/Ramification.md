Let $X,Y$ be curves ([[Curve (Scheme)]]), $f:X\rightarrow Y$ a finite morphism ([[Finite Morphisms of Schemes]]) and $P\in X$ .
Then let $Q = f(P)$, $t \in \mathcal{O}_Q$ be a local parameter at $Q$ ([[Induced Morphism on Divisors]]). We consider $t$ as an element of $\mathcal{O}_P$ via the natural map $f^{\#}:\mathcal{O}_Q\rightarrow\mathcal{O}_P$.
Then the *ramification index* $e_P$ of $f$ at $P$ is defined as 
$$ e_P = \nu_P(t)$$
where $\nu_P$ is the valuation ([[Valuation Ring]]) associated to $\mathcal{O}_P$.
If $e_P > 1$ we say $f$ is *ramified* at $P$ and $Q$ is a *branch point* of $f$.
If $e_P = 1$ we say $f$ is unramified at $P$.
If $\text{char}(K) = 0$ ([[Characteristic of a Field]]) or $\text{char}(k) = p$ and $p$ does not divide $e_P$ we say the ramification is *tame*. Otherwise it is *wild*.

For a finite, separable morphism of curves $f:X\rightarrow Y$ ([[Finite Morphisms of Schemes]], [[Separated Morphisms]]) we have 
* $\Omega_{X/Y}$ is a torsion sheaf on $X$ with support equal to the ramification points of $f$ ([[Sheaf of relative differentials]]). In particular $f$ is ramified at finitely many points
* for $P\in X$, the stalk $(\Omega_{X/Y})_P$ is a principal $\mathcal{O}_P$-module of finite length $\nu_P(dt/du)$ 
* if $f$ is tamely ramified at $P$, then $\text{length}(\Omega_{X/Y})_P = e_P -1$ 
* if $f$ is wildly ramified then $length(\Omega_{X/Y})_P > e_P-1$ 