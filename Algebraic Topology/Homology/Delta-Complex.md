A *$\Delta$-Complex* on a [[Topological Space]] $X$, is a collection $\Delta$ of maps $\sigma_{\alpha} : \Delta^n \rightarrow X$ ([[Simplices]]) with $n$ depending on $\alpha$ s.t. the following holds

1. The restriction ([[Function#Restriction]]) $\sigma_{\alpha}|_{\mathring{\Delta}^n}$ is injective ([[Function#Injections Surjections and Bijections]]) and each $x\in X$ is in *exactly* one image of such a restriction
2. Each restriction of $\sigma_{\alpha}$ to a face of $\Delta^n$ is also in the $\Delta$-complex, i.e. there is a $\beta$ s.t. $\sigma_{\beta}\in \Delta$, where we identify the face of $\Delta^n$ with $\Delta^{n-1}$ keeping the vertex order.
3. Any set $A\subseteq X$ is open iff $\sigma_{\alpha}^{-1}(A)$ is open in $\Delta^n$ for each $\sigma_{\alpha}$

Given a $\Delta$-complex on a space $X$, we can identify $X$ with the quotient space of a collection of disjoint simplices $\Delta^n_{\alpha}$ by identifying the faces of $\Delta^n_{\alpha}$ with the corresponding $\Delta^{n-1}_{\beta}$ given by the restriction (2.).
If there is a $\Delta$-complex on $X$, then $X$ has to be a [[Hausdorff Space]]