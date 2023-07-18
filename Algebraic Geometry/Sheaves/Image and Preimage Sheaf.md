Let $f:X\rightarrow Y$ be a [[Continous Function]] between [[Topological Space]]s and $\mathcal{F}$ a [[Sheaf]] on $X$. Then the *direct image sheaf* $f_*(\mathcal{F})$  is the sheaf on $Y$ defined by $f_*\mathcal{F}(V) = \mathcal{F}(f^{-1}(V))$ for all open sets $V\subseteq Y$. 

For a sheaf $\mathcal{G}$ on $Y$, the *inverse image sheaf* $f^{-1}\mathcal{G}$ on $X$ is the sheaf associated to the presheaf ([[Associated Sheaf]]) $U\mapsto lim_{V\supseteq f(U)}\mathcal{G}(V)$.

$f_*$ is a [[Functor]] from the [[Category]] of sheaves on $X$ to the category of sheaves on $Y$.

If $Z\subseteqq X$ is a subspace with induced topology, and $i:Z\hookrightarrow X$ the inclusion. Then for any sheaf $\mathcal{F}$ on $X$, $i^{-1}\mathcal{F}$ is called the *restriction* of $\mathcal{F}$ on $Z$ , often denoted $\mathcal{F}_Z$. Then $\mathcal{F}_{Z,P}=\mathcal{F}_P$  

The image of a [[Sheaf of Modules]] is again a sheaf of modules. The *inverse image* of a morphism $f:\mathcal{F}\rightarrow\mathcal{G}$ of sheaves of modules is defined as $f^*\mathcal{G} = f^{-1}\mathcal{G} \otimes_{f^{-1}\mathcal{O}_Y} \mathcal{O}_X$ i 