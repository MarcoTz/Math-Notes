A *ring homomorphism* is a [[Homomorphism]] between [[Ring]]s, i.e. a map $f:R\rightarrow S$ s.t. 

1. $f$ is a [[Group Homomorphism]] of the additive groups of $R$ and $S$
2. $f(1) = 1$
3. $f(xy) = f(x)f(y)$

A ring homomorphism has the following properties

* for a subring $R^{\prime} \subseteq R$, $f(R^{\prime})$ is a subring of $S$
* for a subring $S^{\prime}\subseteq S$, $f^{-1}(S^{\prime})$ is a subring of $R$
* for an ideal $I\subseteq R$ , $f(I)$ is an ideal of $S$
* for an ideal $J\subseteq f(R)$, $f^{-1}(J)$ is an ideal of $R$. In particular $ker f$ is an ideal of $R$

Ring homomorphisms inherit the terms for general homomorphisms, see [[Homomorphism#Monomorphisms Epimorphisms and Isomorphisms]]

#### Homomorphism Theorem

Let $\varphi : R\rightarrow R^{\prime}$ be a ring homomorphism, then $ker \varphi$ is an [[Ideal]] of $R$ and 

$R/ker\varphi \cong \varphi(R)$ 

(see [[Quotient Ring]])