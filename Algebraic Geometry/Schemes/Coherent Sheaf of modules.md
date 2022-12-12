Let $(X,\mathcal{O}_X)$ be a [[Scheme]]. A sheaf of $\mathcal{O}_X$-modules ([[Sheaf of Modules]]) is called *quasi-coherent*, if $X$ can e covered by open affine subsets $U_i = SpecA_i$ s.t. for each $i$, there is an $A_i$-[[Module]] with $\mathcal{F}|_{U_i} \cong \tilde{M}_i$ ([[Associated Sheaf of Modules]]).
If each $M_i$ can ge chosen to be finitely generated, we say $\mathcal{F}$ is *coherent*

For a quasi-coherent sheaf $\mathcal{F}$ on an affine scheme $X=Spec A$ ([[Spectrum]]), we have
* If for $s\in\Gamma(X,\mathcal{F})$ and $f\in A$ we have $s|_{D(f)} = 0$, there is some $n$ with $f^ns=0$
* Given some $s\in \mathcal{F}(D(f))$ for some $f\in A$, there is some $n$ s.t. $f^ns$ extends to a global section of $\mathcal{F}$ 

A scheaf of $\mathcal{O}_X$-modules $\mathcal{F}$ is quasicoherent iff for each open affine subset $SpecA=U\subseteq X$, there is some $A$-module $M$ with $\mathcal{F}|_U \cong \tilde{M}$.
If $X$ is a [[Noetherian Scheme]] then $\mathcal{F}$ is coherent iff it is quasi-coherent and each module $M$ on open affine subsets of $X$ is finitely generated.

If $0\rightarrow \mathcal{F}^{\prime} \rightarrow \mathcal{F} \rightarrow \mathcal{F}^{\prime\prime} \rightarrow 0$ is an [[Exact Sequence]] of $\mathcal{O}_X$-modules with $\mathcal{F}^{\prime}$ quasi-coherent, the sequence $0\rightarrow \Gamma(X,\mathcal{F}^{\prime}) \rightarrow \Gamma(X,\mathcal{F}) \rightarrow \Gamma(X,\mathcal{F}^{\prime\prime}) \rightarrow 0$ 

Images, kernel, cokernels ([[Image and Preimage Sheaf]]) and extensoins of quasi-coherent schemes are quasi-coherent, and on noehterian schemes the same is true for coherent schemes.