Let $X$ be a [[Topological Space]], and $\Gamma(X,\cdot):\mathfrak{Ub}(X) \rightarrow \mathfrak{Ub}$ ([[Category]],[[Ringed Space]]). Then the *cohomology functors* $H^i(X,\cdot)$ are the right-derived functors ([[Right Derived Functor]]) of $\Gamma(X,\cdot)$. 
For a [[Sheaf]] $\mathcal{F}$, the groups $H^i(X,\mathcal{F})$ are called *cohomology groups* of $\mathcal{F}$.

If $\mathcal{F}$ is a [[Flasque Sheaf]] on a topological space $X$, $H^i(X,\mathcal{F})=0$ for all $i>0$.

For a ringed space $(X,\mathcal{O}_X)$, the derived functors of the functor $\Gamma(X,\cdot):\mathfrak{Mod}(X) \rightarrow \mathfrak{Ub}$ coincide with the cohomology functors $H^i(X,\cdot)$.

On a [[Noetherian Space]] $X$ with $dim(X)=n$, we have $H^i(X,\mathcal{F}) = 0$ for all $i>0$ and sheaf $\mathcal{F}$.

Let $X$be a noetherian space and $(\mathcal{F}_{\alpha})$ be a direct system ([[Direct Limit]]) [[Abelian Group]]s. Then for each $i\geq 0$, there are natural isomorphisms $\underrightarrow{\lim} H^i(X,\mathcal{F}_{\alpha})\rightarrow H^i(X,\underrightarrow{\lim}\mathcal{F}_{\alpha})$. This also means cohomology commutes with infinite direct sums.

Let $Y$ be a closed subset of $X$, $\mathcal{F}$ a sheaf of abelian groups on $Y$ and let $j:Y\rightarrow X$ be the inclusion. Then $H^i(Y,\mathcal{F}) = H^i(X,j_*\mathcal{F})$, where $j_*\mathcal{F}$ is the extension of $\mathcal{F}$ to $0$ outside $Y$.

On a [[Spectrum]] $X=SpecA$ of a ring $A$, for any quasi-coherent sheaf $\mathcal{F}$ ([[Coherent Sheaf of modules]]) on $X$ and any $i>0$ we have $H^i(X,\mathcal{F})$.

Let $X$ be a noetherian scheme, then the following are equivalent 
* $X$ is affine 
* $H^i(X,\mathcal{F}) = 0$ for all quasi-coherent scheaves $\mathcal{F}$ and $i>0$
* $H^1(X,\mathcal{I}) = 0$ for all coherehnt sheaves of ideals $\mathcal{I}$ ([[Sheaf of Ideals]])

For a [[Noetherian Ring]] $A$ and $X=\mathbb{P}^r_A$ with $r\geq 1$ then 
* The natural map $S\rightarrow \Gamma_*(\mathcal{O}_X) = \bigoplus_{n\in \mathbb{Z}} H^0(X,\mathcal{O}_X(n))$ is an isomorphism.
* $H^i(X,\mathcal{O}_X(n)) = 0$ for $0<i<r$ and $n\in \mathbb{Z}$
* $H^r(X,\mathcal{O}_X(-r-1) \cong A$
* the natural map $H^0(X,\mathcal{O}_X(n)) \times H^r(X,\mathcal{O}_X(-n-r-1)) \rightarrow H^r(X,\mathcal{O}_X(-r-1)) \cong A$ is a perfect pairing ([[Pairing]]) of finitely generated free $A$-modules for each $n\in \mathbb{Z}$ 

If $X$ is a [[Projective Scheme]] over a noetherian ring $A$ s.t. $\mathcal{O}_X(1)$ ([[Twisting Sheaf]]) is a very ample ([[Ample Sheaves]]) invertible ([[Free Scheaf of Modules]]) on $X$ over $Spec A$ ([[Scheme over a Scheme]]). Then
* for each $i\geq 0$, $H^i(X,\mathcal{F})$ is a finitely generated $A$-module
* there is some $n_0$ s.t. for each $i>0$ and $n\geq n_0$, $H^i(X,\mathcal{F}(n)) = 0$ 