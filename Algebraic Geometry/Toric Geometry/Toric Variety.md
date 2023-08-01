A *Toric Variety* is an [[Abstract Variety]] $X$ that is irreducible ([[Irreducible Sets]]) and contains a torus ([[Algebraic Torus]]) $T_N$ as a Zariski-open subset s.t. the action of $T_N$ on itself extends to an action of $T_N$ on $X$ s.t. the map $T_N\times X \rightarrow X$ defined by the action is a morphism.
Any afffine or projective toric variety is also a toric variety ([[Affine Toric Variety]],[[Projective Toric Variety]] )

Given a [[Fan]] $\Sigma$, for each $\sigma\in \Sigma$ we have the affine toric variety $U_{\sigma} = Spec(\mathbb{C}[S_{\sigma}])$. For $\sigma_1,\sigma_2\in \Sigma$ with $\tau = \sigma_1\cap\sigma_2$ we have an isomorphism $g_{\sigma_2\sigma_1} : (U_{\sigma_1})_{\chi^m} \cong (U_{\sigma_2})_{\chi^{-m}}$ which is the identity on $U_{\tau}$. This defines an abstract variety $X_{\Sigma}$ which is a toric variety associated to the fan $\Sigma$.
The variety $X_{\Sigma}$ is a normal, separated toric variety ([[Normal Variety]], [[Separated Morphisms]]).

If $P\subseteq M_{\mathbb{R}}$ is a full-dimensional [[Lattice]] [[Polytope]], we have $X_P \cong X_{\Sigma_P}$ where $\Sigma_P$ is the [[Normal Fan]] of $P$.

For two fans $\Sigma_1$ in $(N_1)_{\mathbb{R}}$ and $\Sigma_2$ in $(N_2)_{\mathbb{R}}$, $\Sigma_1\times\Sigma_2 = \{\sigma_1\times \sigma_2 | \sigma_1\in \Sigma_1,\sigma_2\in\Sigma_2\}$ is a fan in $(N_1\times N_2)_{\mathbb{R}}$ and $X_{\Sigma_1\times\Sigma_2} \cong X_{\Sigma_1} \times X_{\Sigma_2}$.

We have 
* $X_{\Sigma}$ is smooth ([[Singularities]]) iff $\Sigma$ is smooth
* $X_{\Sigma}$ is an orbifold i.e. it has only finite quotient singularities iff $\Sigma$ is simplicial 
* $X_{\Sigma}$ is compact in the classical topology iff $\Sigma$ is complete

For a toric variety $X_{\Sigma}$ the following are equivalent 
* $X_{\Sigma}$ is compact in the classical topology ([[Compactness]])
* $X_{\Sigma}$ is complete ([[Variety]])
* The limit $\lim_{t\rightarrow 0} \lambda^u(t)$ exists in $X_{\Sigma}$ for all $u\in N$ ([[One-Parameter Subgroup]])
* $\Sigma$ is complete, i.e. $|\Sigma|=\bigcup_{\sigma\in\Sigma}\sigma =N_{\mathbb{R}}$ 

