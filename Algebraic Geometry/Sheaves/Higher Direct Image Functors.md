Let $f:X\rightarrow Y$ be a [[Continous Function]] of [[Topological Space]]s, then the *Higher Direct Image Functors* $R^if_* : \mathcal{Ub}(X) \rightarrow \mathcal{Ub}(Y)$ are the right-derived functors ([[Right Derived Functor]]) of the direct image functor $f_*$ ([[Image and Preimage Sheaf]]) .
This is well-defined because $f_*$ is left-exact ([[Exact Functor]]) and $\mathcal{U}(X)$ has enough injectives ([[Injective Object]]).

For any $\mathcal{F} \in \mathcal{Ub}(X)$, $R^if_*(\mathcal{F})$ is the sheaf associated to the presheaf ([[Associated Sheaf]]) $V\mapsto H^i(f^{-1}(V),\mathcal{F}\mid_{f^{-1}(V)})$ on $Y$.
For $V\subset Y$ open, we have $R^if_*(\mathcal{F})\mid_V = R^if_*^{\prime}(\mathcal{F}\mid_{f^{-1}(V)})$ with $f^{\prime} : f^{-1}(V) \rightarrow V$ restricted map.
For $\mathcal{F}$ flasque, $R^if_*(\mathcal{F}) = 0$ for all $i>0$.
If $Y=Spec A$ ([[Spectrum]]) and $\mathcal{F}$ quasi-coherent ([[Coherent Sheaf of modules]]), then $R^if_*(\mathcal{F}) \cong H^i(X,\mathcal{F})^{\sim}$ ([[Associated Sheaf of Modules]]).

Let $f:X\rightarrow Y$ be a projective morphism ([[Projective Morphism]]) of noetherian schemes ([[Noetherian Scheme]]), with $\mathcal{O}_X(1)$ very ample invertible ([[Ample Sheaves]], [[Free Scheaf of Modules]]) on $X$ over $Y$ and $\mathcal{F}$ coherent ([[Coherent Sheaf of modules]]) on $X$. Then 
* for $n\gg 0$, the natural map $f^*f_*(\mathcal{F}(n)) \rightarrow \mathcal{F}(n)$ is surjective 
* for $i\geq 0$, $R^if_*(\mathcal{F})$ is coherent on $Y$ 
* for $i>0$ and $n\gg 0$, $R^if_*(\mathcal{F}(n)) = 0$ 