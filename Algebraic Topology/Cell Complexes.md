A *n-cell* is the unit sphere $S^n$, where $S^0$ is simply a point.
Given a discrete set $X^0$ with points regarded as $0$-cells we can inductively construct the following: 

* Given $X^{n-1}$ construct the *$n$-skeleton* $X^{n}$ by attaching $n$-cells $e_{\alpha}^n$ via maps $\varphi_{\alpha}:S^{n-1} \rightarrow X^{n-1}$, which means $X^n$ is the quotient space ([[Topology/Quotient Space]]) of the [[Disjoint Union]] $X^{n-1}\bigsqcup D_{\alpha}^n$ of $X^{n-1}$ and a collection of $n$-disks $D_{\alpha}^n$ ($intS^{n-1}\bigcup S^{n-1}$ ([[Topological Space#Interior]]) of $S^{n-1}$) with the identifications $x\sim \varphi_{\alpha}(x)$ for $x\in S^n$. 
* After $n$ steps, either set $X = X^n$ or continue indefinitely, setting $X=\bigcup_n X^n$
  In the first case, $X$ is giventhe induced topolgy by the discrete topology ([[Topological Space]]) on $X^0$ after the constructon above. In the latter case, $X$ is given the *weak topolgy*: $A\subseteq X$ is open (or closed) iff $A\cap X$ is open (or closed) for each $n$.

A space constructed in this way is called a *cell complex* or *CW complex*.
If $X=X^n$ for some $n$, we say $X$ is *finite-dimensional* and say $dimX = n$. Otherwise we say $dimX=\infty$. This is equal to the [[Lebesgue Covering Dimension]] of $X$.

For each cell $e_{\alpha}^n$ we have the *characteristic map* of $e_n^{\alpha}$, $\Phi_{\alpha}: D_{\alpha}^n \rightarrow X$, which is the extension of the attaching map $\varphi_{\alpha}$ defined by the composition $D_{\alpha}^n \hookrightarrow \bigsqcup_{\alpha}D_{\alpha}^n\rightarrow X^n \hookrightarrow X$ where the middle map is the quotient map defining $X$.

A *subcomplex* of a cell complex $X$ is a closed subspace $A\subseteq X$, that is the union of cells of $X$. $A$ then also has a cell structure induced by the cell structure of $X$. A pair $(X,A)$ of a cell complex and a subcomplex is called *CW pair*.

### Constructions on CW Complexes

If $X$ and $Y$ are cell complexes, then the [[Product Space]] $X\times Y$ is also a cell complex. 

If $(X,A)$ is a CW pair, then the quotient space $X/A$ is also a cell complex.

From this, we can see that the [[Suspension]],[[Join]],[[Cone]],[[Wegde Sum]], and [[Smash Product]] of CW pairs are also CW pairs

### Homology and Cohomology

If $h^*$ is an unreduced cohomology theory ([[Cohomology]]) on the category of CW pairs with $h^n($point$)=0$ for $n\neq 0$, then there are natural isomorphisms $h^n(X,A) \cong H^n(X,A;h^0($point$))$ for all CW pairs $(X,A)$ and all $n$.
The same is true for [[Homology]].
