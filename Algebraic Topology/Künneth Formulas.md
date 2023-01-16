
### Cohomological 

The [[Cross Product]] on [[Cohomology]] extends to a [[Ring Homomorphism]]

$$H^*(X;R)\otimes H^*(Y;R)\rightarrow H^*(X\times Y;R)$$
where multiplication on the tensor product of [[Graded Ring]]s is defined as $(a\otimes b)(c\otimes d) = (-1)^{|b||c|}ac\otimes bd$ 
This cross product on tensor products is an isomorphism of rings if $X$ and $Y$ are [[Cell Complexes]] and $H^k(Y;R)$ is a finitely generated free $R$-[[Module]] for all $k$.

### Homological

### Homological Künneth Formula

If $R$ is a principal ideal domain ([[Ideal#Principal Ideal]])  and [[Chain Complexes]] $C$ and $C^{\prime}$ are free $R$-modules ([[Module#Free Modules]]) then we have the following natural split short exact sequence ([[Exact Sequence]]) for each $n$

$$ 0 \rightarrow \bigoplus_i (H_i(C)\otimes_R H_{n-1(C^{\prime})}) \rightarrow H_n(C\otimes_R C^{\prime}) \rightarrow \bigoplus_i (Tor_R(H_i(C),H_{n-i-1}(C^{\prime}\rightarrow 0$$ (see [[Tensor Product]],[[Chain Complexes#Cochain Complex]],[[Universal Coefficient theorem for homology]])
In particular, if $R$ is a field, all $Tor$ terms are $0$ and we get isomorphisms for each $n$

### Topological

If $X$ and $Y$ are [[Cell Complexes]] and $R$ a principal ideal domain, there are natural split short exact sequences for each $n$

$$ 0 \rightarrow \bigoplus_i (H_i(X;R)\otimes_R H_{n-i}(Y;R))\rightarrow H_n(X\times Y;R)\rightarrow \bigoplus_i Tor_R (H_i(X;R),H_{n-i-1}(Y;R)) \rightarrow 0 $$ 
In particular, if $R$ is a field, this gives isomorphisms.