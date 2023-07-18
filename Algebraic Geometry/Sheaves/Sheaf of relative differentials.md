Let $f:X\rightarrow Y$ be a morphism of [[Scheme]]s and $\Delta: X\rightarrow X\times_Y X$ the diagonal morphism. Then $\Delta(X)$ is a closed subscheme of an open subset $W$ of $X\times_Y X$. 
Let $\mathcal{I}$ be the [[Sheaf of Ideals]] of $\Delta(X)$ in $W$. Then the *sheaf of relative differentials* of $X$ over $Y$ is the sheaf $\Omega_{X/Y} = \Delta^*(\mathcal{I}/\mathcal{I}^2)$ on $X$.

$\Omega_{X/Y}$ has a natural structure of a $\mathcal{O}_{X}$-[[Module]] ([[Sheaf of Modules]]) and it is quasi-coherent ([[Coherent Sheaf of modules]]). If $Y$ is noetherian ([[Noetherian Scheme]]) and $f$ is of finite type ([[Finite Morphisms of Schemes]]) then $\Omega_{X/Y}$ is coherent.

Let $f:X\rightarrow Y$ and $g:Y^{\prime}\rightarrow Y$ be morphisms and $f^{\prime}:X^{\prime}=X\times_Y Y^{\prime}\rightarrow Y^{\prime}$ be obtained by base extension ([[Base Extension]]). Then $\Omega_{X^{\prime}/Y^{\prime}}\cong g^{\prime*} (\Omega_{X/Y})$ where $g^{\prime}:X^{\prime}\rightarrow X$ is the first projection.

Let $f:X\rightarrow Y$ and $g:Y\rightarrow Z$ be morphisms of schemes. Then there is an [[exact sequence]] of sheaves on $X$
$$ f^*\Omega_{Y/Z} \rightarrow \Omega_{X/Z} \rightarrow \Omega_{X/Y} \rightarrow 0$$ 
Let $f:X\rightarrow Y$ be a morphism and $Z$ a closed subscheme of $X$ with ideal sheaf $\mathcal{I}$. Then there is an exact sequence of sheaves on $Z$
$$ \mathcal{I}/\mathcal{I}^2 \xrightarrow{\delta} \Omega_{X/Y}\otimes \mathcal{O}_Z \rightarrow \Omega_{Z/Y}\rightarrow 0$$ 
Let $A$ be a ring, $Y=Spec A$ ([[Spectrum]]) and $X=\mathbb{P}^n_A$ ([[Projective Space]]). Then there is an exact sequence of sheaves on $X$ 
$$ 0 \rightarrow \Omega_{X/Y} \rightarrow \mathcal{O}_X(-1)^{n+1} \rightarrow \mathcal{O}_X \rightarrow 0$$

If $X$ is an irreducible separated ([[Separated Morphisms]]) scheme of finite type over an algebraically closed [[Field]] $k$, $\Omega_{X/k}$ is a locally free sheaf of rank $n=dimX$ ([[Free Scheaf of Modules]]) iff $X$ is a nonsingular variety over $k$ ([[Singularities]])