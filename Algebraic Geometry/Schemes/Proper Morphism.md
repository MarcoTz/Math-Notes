
A morphism $f:X\rightarrow Y$ of [[Scheme]]s is *proper* if it is a [[Separated Morphisms]],of finite type ([[Finite Morphisms of Schemes]]) and universally closed. 
Universally closed means $f$ is a closed map ([[Open and Closed Maps]]) and for any morphism $Y^{\prime}\rightarrow Y$, the corresponding morphism $f^{\prime}:X^{\prime}\rightarrow Y^{\prime}$ obtained from [[Base Extension]] is also closed.

### Valuative Criterion for Properness 

Let $f:X\rightarrow Y$ be a morphism of finite type with $X$ a [[Noetherian Scheme]]. Then $f$ is proper iff for every valuation ring $R$ with [[Quotient Field]] $K$ and every morphisms $U\rightarrow X$ and $T\rightarrow Y$ commuting with $i$ and $f$, there is at most one morphism $T\rightarrow X$ making the following diagram commutative

![[Proper Morphism Diagram.png]]

Here $U=SpecK$, $T=SpecR$ and $i$ is the morphism induced by the inclusion $R\hookrightarrow K$.
