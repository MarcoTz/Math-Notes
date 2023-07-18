Let $f:X\rightarrow Y$ be a morhpism of [[Scheme]]s and $\mathcal{F}$ and $\mathcal{O}_X$-module ([[Sheaf of Modules]]). 
Then $\mathcal{F}$ is *flat* over $Y$ at $x\in X$ if $\mathcal{F}_x$ is a flat $\mathcal{O}_{f(x),Y}$-module ($\mathcal{F}_x$ is a $\mathcal{O}_{f(x),Y}$-module via $f^{\#}:\mathcal{O}_{f(x),Y}\rightarrow \mathcal{O}_{x,X}$).
If $\mathcal{F}$ is flat over all $x\in X$, we say $\mathcal{F}$ is flat over $Y$, and if $\mathcal{O}_X$ is flat over $Y$ we say $X$ is flat over $Y$.

We have the following properties 
* open immersions are flat ([[Open and Closed Subschemes]])
* Let $f:X\rightarrow Y$ be a morphism, $\mathcal{F}$ and $\mathcal{O}_X$-module flat over $Y$ and $g:Y^{\prime}\rightarrow Y$ another morphism. Let $X^{\prime} = X\times_Y Y^{\prime}$ ([[Fibred Product]]), $f:X^{\prime} \rightarrow Y^{\prime}$ the second projection and $\mathcal{F}^{\prime} : p_1^*(\mathcal{F})$. Then $\mathcal{F}^{\prime}$ is flat over $Y^{\prime}$
* Let $f:X\rightarrow Y$ and $g:Y\rightarrow Z$ be morphisms, $\mathcal{F}$ a $\mathcal{O}_X$-module flat over $Y$ and $Y$ flat over $Z$. Then $\mathcal{F}$ is flat over $Z$
* Let $A\rightarrow B$ be a ring homomorphism, $M$ a $B$-module, $f:X=Spec B \rightarrow Y=Spec A$ ([[Spectrum]]) the corresponding scheme morphism and $\mathcal{F} = \tilde{M}$ ([[Associated Sheaf of Modules]]). Then $\mathcal{F}$ is flat over $Y$ iff $M$ is flat over $A$
* Let $X$ be a [[Noetherian Scheme]] and $\mathcal{F}$ a coherent ([[Coherent Sheaf of modules]]) $\mathcal{O}_X$-module. Then $\mathcal{F} is flat over $X$ iff it is locally free ([[Free Scheaf of Modules]]).
* Let $f:X\rightarrow Y$ be a flat morphism of schemes of finite type ([[Finite Morphisms of Schemes]]) over a [[Field]] $k$ ([[Scheme over a Scheme]]). Then $dim_x(X_y) = dim_x(X) - dim_y Y$ (where $X_y$ is the fiber of $f$ over $y$ in $X$)