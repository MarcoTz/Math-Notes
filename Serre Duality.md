Let $k$ be a [[Field]], $X=\mathbb{P}^n_k$ ([[Projective Space]]), then 
* $H^n(X,\omega_X) \cong k$ ([[Cohomology Functor]],[[Canonical Sheaf]])
* For any coherent sheaf $\mathcal{F}$ on $X$ ([[Coherent Sheaf of modules]]), the natural pairing ([[Pairing]]) $Hom(\mathcal{F},\omega)\times H^n(X,\mathcal{F})\rightarrow H^n(X,\omega) \cong k$ is a perfect pairing of finite-dimensional $k$-vector spaces ([[Vector Space]])
* For $i\geq 0$ there is a natural functorial ([[Functor]]) isomorphism $Ext^i(\mathcal{F},\omega) \xrightarrow{\sim} H^{n-1}(X,\mathcal{F})^{\prime}$ where $^{\prime}$ is the dual vector space.

Let $X$ be a [[Projective Scheme]] of dim $n$ over an algebraically closed [[Field]] $k$ with [[Dualizing Sheaf]] $\omega_X^{\circ}$ and $\mathcal{O}(1)$ ([[Twisting Sheaf]]) very ample ([[Ample Sheaves]]). Then
* for $i\geq 0$ and $\mathcal{F}$ coherent on $X$ there are natural functorial maps $\theta^i:Ext^i(\mathcal{F},\omega_X^{\circ}) \rightarrow H^{n-1}(X,\mathcal{F})^{\prime}$ s.t. $\theta^0$ is the isomorphism from the dualizing sheaf 
* The following are equivalent  
	*  $X$ is Cohen-Macauley ([[Cohen-Macaulay Ring]]) and equidimensional ([[Irreducible Sets]])
	* for $\mathcal{F}$ locally free ([[Free Scheaf of Modules]]) on $X$ we have $H^i(X,\mathcal{F}(-q)) = 0$ for $i<n$ and $q\gg 0$ 
	* The maps $\theta^i$ are isomorphisms for all $i\geq 0$ and $\mathcal{F}$ coherent on $X$