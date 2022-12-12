Let $X$ be a [[Topological Space]]. Then a *presheaf* $\mathcal{F}$ of [[Abelian Group]]s, [[Ring]]s, or any other object of a [[Category]] consists of the following 

* for every open $U\subseteq X$, an object $\mathcal{F}(U)$ 
* for every inclusion $V\subseteq U$ of open subsetq $X$ a morphism $\rho_{UV}: \mathcal{F}(U)\rightarrow \mathcal{F}(V)$ 

Satisfying the conditions 

 * $\mathcal{F}(\emptyset) = 0$ 
 * $\rho_{UU}=\mathbb{1}$ for all $U$ 
 * If $W\subseteq V \subseteq U$ then $\rho_{UW} = \rho_{VW}\circ \rho_{UV}$ 

In other words, a presheaf is a contravariant functor from $\mathcal{Top}(X)$ to any other category (i.e. abelian groups, rings, etc..). Here $\mathcal{Top}(X)$ is the category whose objects are the open subsets of $X$ and the only morphisms are inclusion maps.

The objects $\mathcal{F}(U)$ are called *sections* of $\mathcal{F}$ over $U$, sometimes denoted $\Gamma(U,\mathcal{F})$.
The maps $\rho_{UV}$ are called *restriction maps*, sometimes written $s|_V$ instead of $p_{UV}(s)$ for $s\in\mathcal{F}(U)$ 

A preasheaf is a *sheaf*, if it additionally satisfies the following 

* If $U$ is an open set with an open covering $\{V_i\}$ and $s\in\mathcal{F}(U)$ with $s|_{V_i}=0$ for all $i$, then $s=0$ 
* If $U$ is an open set with an open covering $\{V_i\}$ and $s_i\in\mathcal{F}(V_i)$ for all $i$ s.t. $s_i|_{V_i\cap V_j} = s_j|{V_i\cap V_j}$, then there is some $s\in\mathcal{F}(U)$ with $s|_{V_i} = s_i$ for each $i$. 

By the first condition, this $s$ is unique. 

For a presheaf $\mathcal{F}$ on $X$ and $P\in X$, the *stalk* $\mathcal{F}_P$ of $\mathcal{F}$ at $P$ is the [[Direct Limit]] of $\mathcal{F}(U)$ for all $U$ open containing $P$ via the restriction maps $\rho$.

### Subsheaves

A *subsheaf* of a sheaf $\mathcal{F}$ is a sheaf $\mathcal{F}^{\prime}$ s.t. for every open set $U$, $\mathcal{F}^{\prime}(U)$ is a subgroup (or subring, etc) of $\mathcal{F}(U)$, and the restriction maps of $\mathcal{F}^{\prime}$ are induced by the restriction maps of $\mathcal{F}$.
