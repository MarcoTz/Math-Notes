Let $f:X\rightarrow Y$ be a [[Continous Function]] between path-connected [[Topological Space]]s ([[Path Connectedness]]).
Then a *Moore-Postnikov Tower* is a commutative diagram below satisfying: 
![[Moore-Postnikov Diagram.png]]

* each composition $X\rightarrow Z_n \rightarrow Y$ is homotopic ([[Homotopy]]) to $f$
* $X\rightarrow Z_n$ induces an isomorphism on $\pi_i$ for $i<n$ and a surjection for $i=n$ ([[Homotopy Groups]])
* $Z_n\rightarrow Y$ induces an isomorphism on $\pi_i$ for $i>n$ and an injection for $i=n$.
* $Z_{n+1} \rightarrow Z_n$ is a [[Fibration]] with fiber $K(\pi_n(F),n)$ where $F$ is the homotopy fiber of $f$ ([[Eilenberg-MacLane Space]])

If $X$ and $Y$ are CW complexes ([[Cell Complexes]]) and $f:X\rightarrow Y$, then there is a Moore-Postnikov Tower unique up to homotopy equivalence.
Iff $\pi_1(X)$ acts trivially on $\pi_n(M_f,X)$ for all $n>1$ ([[Attaching Spaces#Mapping Cylinder]])