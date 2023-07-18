Let $(X,\mathcal{O}_X)$ be a [[Ringed Space]], $\mathcal{F}$ an $\mathcal{O}_X$-module ([[Sheaf of Modules]]). Then $Ext^i(\mathcal{F},\cdot)$ are the right-derived functors ([[Right Derived Functor]]) of $Hom(\mathcal{F},\cdot)$ and $\mathcal{Ext}(\mathcal{F},\cdot)$ are the right-derived functors of $\mathcal{Hom}(\mathcal{F},\cdot)$.

We have $Ext^0 = Hom$
For $\mathcal{I}$ injective ([[Injective Object]]) in $\mathfrak{Mod}(X)$ and $U\subseteq X$ open, $\mathcal{I}\mid_U$ is injective in $\mathfrak{Mod}(U)$. Then we also have $\mathcal{Ext}^i_X(\mathcal{F},\mathcal{G}) \cong \mathcal{Ext}^i_U(\mathcal{F}\mid_U,\mathcal{G}\mid_U)$.

When $\mathcal{F} = \mathcal{O}_X$ and $\mathcal{G}\in\mathfrak{Mod}(X)$ then 
* $\mathcal{Ext}^0(\mathcal{O}_X,\mathcal{G}) = \mathcal{G}$ 
* $\mathcal{Ext}^i(\mathcal{O}_X,\mathcal{G}) = 0$ for $i>0$
* $Ext^i(\mathcal{O}_X,\mathcal{G}) \cong H^i(X,\mathcal{G})$ for $i\geq 0$ ([[Cohomology Functor]])

For an [[Exact Sequence]] $0\rightarrow \mathcal{F}^{\prime} \rightarrow \mathcal{F} \rightarrow \mathcal{F}^{\prime\prime} \rightarrow 0$ in $\mathfrak{Mod}(X)$ and any $\mathcal{G}$ there is a long exact sequence 
$$ 0 \rightarrow Hom(\mathcal{F}^{\prime\prime},\mathcal{G}) \rightarrow Hom(\mathcal{F},\mathcal{G}) \rightarrow Hom(\mathcal{F}^{\prime},\mathcal{G}) \rightarrow Ext^1(\mathcal{F}^{\prime\prime},\mathcal{G}) \rightarrow Ext^1(\mathcal{F},\mathcal{G}) \rightarrow \dots$$ For the $\mathcal{Ext}$ sheaves a similar sequence exists.

If $\mathcal{L}^i$ is a locally free resolution ([[Free Groups#Free resolution]]) of $\mathcal{F}$, then for $\mathcal{G}\in\mathfrak{Mod}(X)$ we have 
$$ \mathcal{Ext}^i(\mathcal{F},\mathcal{G}) \cong h^i(\mathcal{Hom}(\mathcal{L},\mathcal{G}))$$ 