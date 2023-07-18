Let $A$ be a [[Noetherian Ring]], $Y=SpecA$ ([[Spectrum]]), $f:X\rightarrow Y$ a [[Projective Morphism]] and $\mathcal{F}$ a coherent sheaf on $X$ ([[Coherent Sheaf of modules]]), flat over $Y$ ([[Flat Morphism]]). Then we define

$$ T^i(M) = H^i(X,\mathcal{F}\otimes_A M) \text{ for } i\geq 0$$ (see [[Cohomology Functor]],[[Tensor Product]])

Then each $T^i$ is an additive covariant [[Functor]] $\mathfrak{Mod}(A)\rightarrow\mathfrak{Mod}(A)$, exact in the middle ([[Exact Functor]]).
The collection $(T_i)_{i\geq 0}$ form a $\delta$-functor ([[Delta Functor]]).
There also exists a [[Complex]] $L^{\cdot}$ of finitely generated free $A$-modules, bounded above (i.e. $L^n = 0$ for $n$ large enough) with $T^i(M)\cong h^i(L^{\cdot} \otimes_A M)$.

The following conditions are equivalent
* $T^i$ is left exact 
* $W^i= W^i(L^{\cdot})$ is a projective $A$-module, where $W^i(N) = coker(d^{i-1}:N^{i-1} \rightarrow N^i)$ for any complex $N$.
* there is a unique finitely generated $A$-module $Q$ s.t. $T^i(M) = Hom_A(Q,M)$ 

For any $M$ there is a natural map $\varphi:T^i(A) \otimes M \rightarrow T^i(M)$ and the following conditions are equivalent 
* $T^i$ is right exact 
* $\varphi$ is an isomorphism for all $M$ 
* $\varphi$ is surjective for all $M$ 