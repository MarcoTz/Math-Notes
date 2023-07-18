Let $A$ be a [[Ring]] and $M$ an $A$-[[Module]]. Then $M$ is *flat* over $A$ if $N\mapsto M\otimes_A N$ is exact ([[Exact Functor]], [[Tensor Product]]) for $N\in \mathfrak{Mod}(A)$ (i.e. $N$ is another $A$-module).

Flat modules have the following properties 

* $M$ is flat iff for every finitely generated ideal $a\subseteq A$ ([[Ideal]]) the map $a\otimes M \rightarrow M$ is injective
* If $M$ is a flat $A$-module and $A\rightarrow B$ a homomorphism, then $M \otimes_A B$ is flat (Base extension)
* If $B$ is a flat $A$-algebra and $N$ a flat $B$-module, then $N$ is also a flat $A$-module (Transitivity)
* $M$ is flat over $A$ iff $M_p$ is flat over $A_p$ for all $p$ prime ideals of $A$ ([[Localization]])
* If $0\rightarrow M^{\prime} \rightarrow M \rightarrow M^{\prime\prime} \rightarrow 0$ is an [[Exact Sequence]] of $A$-modules with $M^{\prime}$ and $M^{\prime\prime}$ both flat then $M$ is flat. If instead $M$ and $M^{\prime\prime}$ are flat, $M^{\prime}$ is also flat.
* A finitely generated module $M$ over a local [[Noetherian Ring]] ([[Local Ring]]) $A$ is flat iff it is free