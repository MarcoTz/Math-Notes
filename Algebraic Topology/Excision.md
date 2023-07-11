Various theorems about [[Homology]], [[Cohomology]] and [[Homotopy Groups]].

### Cohomology 

Let $X$ be a [[Topological Space]] with subspaces $Z\subseteq A\subseteq X$ s.t. $clZ\subseteq intA$. Then the inclusion $i:(X\setminus Z,A\setminus Z)\xhookrightarrow{} (X,A)$ induces isomorphisms $i^*:H^n(X,A;G)\rightarrow H^n(X\setminus Z,A\setminus Z)$

### Relative Homology

Let $Z\subseteq A \subseteq X$ be subspaces of a topological space $X$ s.t. $cl(Z) \subseteq int(A)$. Then the inclusion $(X\setminus Z,A\setminus Z) \hookrightarrow (X,A)$ induces isomorphisms $H_n(X\setminus Z,A\setminus Z)\rightarrow H_n(X,A)$

### Excision for Homotopy 

Let $X$ be a CW complex ([[Cell Complexes]]) s.t. $X = A\cup B$ with $C=A\cap B \neq \emptyset$ connected, with $(A,C)$ $m$-connected, $(B,C)$ $n$-connected, $m,n\geq 0$ ([[n-connectedness]]).
Then $\pi_i(A,C) \rightarrow \pi_i(X,B)$ induced by the inclusion is an isomorphism for $i<m+n$ and a surjection for $i=m+n$.

Then the suspension map ([[Suspension]]) $\pi_i(X) \rightarrow \pi_{i+1}(SX)$ is an isomorphism for $i<2n-1$ and a surjection for $i=2n-1$ for any $(n-1)$-connected CW complex $X$.
In particular this holds for $X=S^n$ where $SX = S^{n+1}$.