
Given a [[Field Extension]] $L:K$, $L$ is naturally a [[Vector Space]] over $K$. 
We define 

$Deg(L:K) = [L:K] = dim_K L$ 

If $[L:K]$ is finite, we say $L:K$ is a *finite field extension*. If $[L:K]=2$, we say $L:K$ is a *quadratic extension*

$L:K$ is finite iff there are algebraic ([[Algebraic Field extension]])  elements $a_1,\dots,a_k\in L$ with $L = K(a_1,\dots,a_n)$ (see [[#Simple Extension]])

#### Degree Theorem

If $K\subseteq M \subseteq L$ is a field tower s.t. $L:K$ is finite, then 

$[L:K] = [L:M][M:K]$

In particular, if $[L:K]=[M:K]$ then $L=M$ and by induction, for a field tower $K_1\subseteq \dots \subseteq K_n$ we have $[K_n:K_1] = \Pi_{i=1}^{n-1}[K_{i+1}:K_i]$