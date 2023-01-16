
A graded [[Algebra]] ([[Graded Ring]]) $A=\bigoplus_{n\geq 0} A^n$ over a commutative [[Ring]] satisfying the following axioms is called a Hopf algebra

* There is an identity element $1\in A^0$, s.t. $R\rightarrow A^0$ , $r\mapsto r\cdot 1$ is an isomorphism. In this case we say $A$ is *connected*
* there is a *diagonal* or *coproduct* $\Delta:A\rightarrow A\otimes A$, a homomorphism of graded algebras with $\Delta(\alpha) = \alpha \otimes 1 + 1\otimes \alpha + \sum_i \alpha^{\prime}_i \otimes \alpha_i^{\prime\prime}$ where $|\alpha_i^{\prime}|>0$ and $|\alpha_i^{\prime\prime}|>0$ for all $\alpha$ with $|\alpha|>0$ 

The [[Cohomology Ring]] $H^*(X;R)$ where $R$ is commutative and $X$ is an [[H-Space]] that is path-connected ([[Path Connectedness]]) and $H^n(X;R)$ is a finitely generated $R$-module for each $n$ is an example of an Hopf-algebra. The coproduct in this case is the map $\mu^*:H^*(X;R)\rightarrow H^*(X\times X;R)$ induced by the multiplication on $X$ followed by the [[Cross Product]] isomorphism.

A commutative, associative Hopf-algebra $A$ over a [[Field]] $F$ with characteristic $0$ ([[Characteristic of a Field]]) s.t. $A^n$ is finite-dimensional over $F$ for each $n$, is isomorphic as an algebra to the tensor product of an exterior algebra ([[Tensor Operations on Modules]]) on odd dimensional generators and a polynomial algebra on even-dimensional generators.
With the same conditions satisfied, but the characteristic of $F$ being $p<\infty$, $A$ is isomorphic to the tensor product of Hopf algebras of the following types
* $F[a]$ with $\alpha$ even-dimensional if $p\neq 2$
* $\bigwedge_F[\alpha]$ with $\alpha$ odd-dimensional
* $F[\alpha]/(\alpha^{p^i})$ with $\alpha$ even-dimensional if $p\neq 2$ 

If $A$ is a Hopf-Algebra over $R$ that is a finitely generated free $R$-module in each dimension, the product $\pi:A\otimes A \rightarrow A$ and coproduct $\Delta:A\rightarrow A\otimes A$ have duals $\pi^*:A^*\rightarrow A*\otimes A^*$ that give $A^*$ the stucture of an $A^*$-algebra.