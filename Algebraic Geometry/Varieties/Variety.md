For a fixed algebraically closed [[Field]] $k$, a *variety* over $k$ is any (quasi-)[[Affine Variety]] or (quasi-)[[Projective Variety]].
A *morphism* $\varphi: X\rightarrow Y$ of two varieties $X$ and $Y$ is a [[Continous Function]] (in the [[Zariski Topology]]), s.t. for any open set $V\subseteq Y$ and any [[Regular Function]] $f:V\rightarrow k$, $f\circ \varphi : \varphi^{-1}(V) \rightarrow k$ is regular.
This defines a [[Category]] of varieties.

An *isomorphism* of varieties is a morphism $\varphi : X\rightarrow Y$ s.t. there is a morphism $\psi : Y\rightarrow X$ with $\varphi \circ \psi = \mathbb{1}_Y$ and $\psi \circ \varphi = \mathbb{1}_X$ 

Two affine varieties $X$ and $Y$ are isomorphic iff $A(X)\cong A(Y)$ 

If $\varphi$ and $\psi$ are two morphisms $X\rightarrow Y$ and there is a nonempty open subset $U\subseteq X$ with $\varphi|_U = \psi_U$ then $\varphi = \psi$.

### Birational Equivalence 

For two  varieties $X$ and $Y$, the following is equivalent 

* $X$ and $Y$ are birationally equivalent ([[Birational Map]])
* there are open subsets $U\subseteq X$ and $V\subseteq Y$ s.t. $U$ and $V$ are isomorphic
* $K(X) \cong K(Y)$ as $k$-algebras ([[Function Field]])

### Projective Dimension Theorem

Let $Y,Z$ be varieties of dimensions $r,s$ in $\mathbb{P}^n$. Then every irreducible component of $Y\cap Z$ has dimension $\geq r+s-n$ and if $r+s-n\geq 0$ then $Y\cap Z$ is nonempty.

### Abstract Variety

Via the functor $t$ ([[Schemes and Varieties]]), any variety over a algebraically closed field $k$, can be identified with its corresponding [[Scheme]], so the term *abstract variety* is used for any separated ([[Separated Morphisms]]) scheme of finite type ([[Finite Morphisms of Schemes]]) over an algebraically closed field $k$. If an abstract variety is proper ([[Proper Morphism]]) over $k$, we say it is *complete*.