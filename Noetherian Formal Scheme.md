A *noetherian formal scheme* is a locally [[Ringed Space]] $(\mathfrak{X},\mathcal{O}_X)$ with a finite open cover $\{\mathfrak{U}_i\}$ s.t. $(\mathfrak{U}_i,\mathcal{O}_{\mathfrak{X}}|_{\mathfrak{U}_i})$ is isomorphic as a locally ringed space to the completion ([[Completion of a Scheme]]) of some [[Noetherian Scheme]] $X$ along a closed subscheme $Y_i$.
A *morphism* of noetherian formal schemes is a morphism of locally ringed spaces.
A [[Sheaf]] $\mathfrak{F}$ of $\mathcal{O}_{\mathfrak{X}}$-modules ([[Sheaf of Modules]]) is *coherent* if there is a finite open cover $\{\mathfrak{U}_i\}$ as above with $\mathfrak{U}_i\cong \hat{X}_i$ and for each $i$ there is a [[Coherent Sheaf of modules]] $\mathcal{F}_i$ on $X_i$ s.t. $\mathfrak{F}|_{\mathfrak{U}_i}\cong \hat{ \mathcal{F}}_i$ ([[Completion of a Sheaf]]) via the isomorphism  $\mathfrak{U}_i\cong \hat{X}_i$.

A noetherian formal scheme is called *affine* if it is obtained from the completion of a single affine noetherian scheme ([[Spectrum]]) along a closed subscheme ([[Open and Closed Subschemes]]).
If $X=Spec A$, $Y=V(I)$ and $X=\hat{X}$ then for any finitely generated $A$-module $M$, we define $M^{\Delta}$ on $\mathfrak{X}$ to be the completion of $\tilde{M}$ on $X$ ([[Associated Sheaf of Modules]]). This is a coherent sheaf on $\mathfrak{X}$.

For a [[Noetherian Ring]] $A$ with [[Ideal]] $I$, $X=Spec A$, $Y=V(I)$ and $\mathfrak{X} = \hat{X}$ we have 
* $\mathcal{I} = I^{\Delta}$ is a [[Sheaf of Ideals]] in $\mathcal{O}_{\mathfrak{X}}$ and for any $n$, $\mathcal{O}_X /\mathcal{I}^n \cong \tilde{(A/I^n)}$ 
* if $M$ is a finitely generated $A$-module, $M^{\Delta} = \tilde{M} \otimes_{\mathcal{O}_X} \mathcal{O}_{\mathfrak{X}}$ 
* The functor $M\mapsto M^{\Delta}$ is an exact functor from the [[Category]] of finitely generated $A$-modules to the category of coherent $\mathcal{O}_{\mathfrak{X}}$-modules

Let $A$ be a noetherian ring with ideal $I$ s.t. $A$ is $I$-adically complete. Let $X=SpecA$, $Y=V(I)$ and $\mathfrak{X} = \hat{X}$. Then the functors $M\mapsto M^{\Delta}$ and $\mathfrak{F} \mapsto \Gamma(\mathfrak{X},\mathfrak{F})$ are exact and inverse to each other, and thus define an equivalence of categories ([[Ideal of Definition]]).
In particular, every coherent $\mathcal{O}_{\mathfrak{X}}$-module $\mathfrak{F}$ is $M^{\Delta}$ for some $M$