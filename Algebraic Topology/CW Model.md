Let $(X,A)$ be a CW pair ([[Cell Complexes]]), then an *$n$-connected CW model* for $(X,A)$ is a $n$-connected ([[n-connectedness]]) CW pair $(Z,A)$ and a map $f:Z\rightarrow X$ with $f|_A =\mathbb{1}_A$ and $f_*:\pi_i(Z)\rightarrow \pi_i(X)$ ([[Homotopy Groups]]) is an isomorphism for $i>n$ and an injection for $i=n$ for all choices of basepiont.

Since $(Z,A)$ is $n$-connected, the map $\pi_i(A)\rightarrow \pi_i(Z)$ is an isomorphism for $i<n$ and a surjection for $i=n$. 
In dimension $n$, the maps $A\hookrightarrow Z\xrightarrow{f} X$ induce a composition $\pi_n(A)\rightarrow \pi_n(Z) \rightarrow \pi_n(X)$ factoring the map $\pi_n(A)\rightarrow \pi_n(X)$ as a surjection followed by an injection.

$n$-connected CW models $f:(Z,A)\rightarrow (X,A)$ exits for every pair $(X,A)$ and $n\geq 0$, and these models can be chosen such that $Z$ is obtained from $A$ by attaching cells of dimension greater than $n$.

Let $f:(Z,A)\rightarrow (X,A)$ be an $n$-connected CW-model, $f^{\prime} : (Z^{\prime},A^{\prime})\rightarrow (X^{\prime},A^{\prime})$ an $n^{\prime}$-connected CW model and $g:(X,A)\rightarrow (X^{\prime},A^{\prime}$) a continuous map. Then if $n\geq n^{\prime}$, there is a map $h:Z\rightarrow Z^{\prime}$ s.t. $h|_A = g$ and $gf \simeq f^{\prime}h$ rel $A$, which is unique up to [[Homotopy]] rel $A$ and which gives a commutative diagram 

![[CW Model Diagram.png]]

As a corollary, an $n$-connected CW model for $(X,A)$ is unique up to homotopy equivalence rel $A$ and thus [[CW Approximation]]s are also unique up to homotopy equivalence.