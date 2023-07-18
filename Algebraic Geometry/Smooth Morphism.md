A morphism $f:X\rightarrow Y$ of [[Scheme]]s of finite type ([[Finite Morphisms of Schemes]]) over $k$ ([[Field]]) is *smooth of relative dimension $n$* if 
* $f$ is flat ([[Flat Morphism]])
* if $X^{\prime}\subseteq X$ and $Y^{\prime}\subseteq Y$ are irreducible ([[Irreducible Sets]]) components s.t. $f(X^{\prime}) \subseteq Y^{\prime}$, then $dimX^{\prime} = dim Y^{\prime} + n$
* for each $x\in X$ we have $dim_{k(x)}(\Omega_{X/Y} \otimes k(x)) = n$ ([[Tensor Product]],[[Relative Differential Forms]])

We have the following properties 
* an open immersion ([[Open and Closed Subschemes]]) is smooth of relative dimension $0$
* if $f:X\rightarrow Y$ is smooth of relative dimension $n$ and $g:Y^{\prime} \rightarrow Y$ is a morphism, then $f^{\prime}:X^{\prime} \rightarrow Y^{\prime}$ obtained by [[Base Extension]] is also smooth of relative dimension $n$
* If $f:X\rightarrow Y$ is smooth of relative dimension $n$ and $g:Y\rightarrow Z$ is smooth of relative dimension $m$, then $g\circ f : X\rightarrow Z$ is smooth of relative dimension $n+m$
* If $X$ and $Y$ are smooth over $Z$ of relative dimensions $n$ and $m$ ([[Scheme over a Scheme]]) respectively, then $X\times_Z Y $([[Fibred Product]]) is smooth over $Z$ of relative dimension $n+m$

If $f:X\rightarrow Y$ is a morphism of schemes of finite type over $k$ ([[Finite Morphisms of Schemes]]) then $f$ is smooth of relative dimension $n$ iff 
* $f$ is flat 
* for $y\in Y$, let $X_{\bar{y}} = X_y \otimes_{k(y)} k(y)^-$ where $k(y)^-$ is the algebraic closure of $k(y)$. Then $X_{\bar{y}}$ is equidimensional ([[Irreducible Sets]]) of dimension $n$ and regular  