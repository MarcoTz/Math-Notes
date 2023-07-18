Let $A$ be a [[Ring]] and $M$ an $A$-[[Module]]. Then the *sheaf associated to $M$* on $SpecA$ ([[Spectrum]]), denoted by $\tilde{M}$ is defined as follows.
For any [[Prime Ideal]] $p\subseteq A$, let $M_p$ be the [[Localization]] of $M$ at $p$. Then for an open $U\subseteq SpecA$, $\tilde{M}(U)$ is the set of functions $s:U\rightarrow \bigsqcup_{p\in U} M_p$ s.t. for each $p\in U$, $s(p)\in M_p$ and such that there is a neighborhood $V$ of $p$ in $U$ and elements $m\in M$, $f\in A$ s.t. for each $q\in V$ with $f\notin q$, we have $s(q) = \frac{m}{f}\in M_q$. This is a [[Sheaf of Modules]] with the natural restriction maps.  

$\tilde{M}$ has the following properties 

* For $p\in X$, $(\tilde{M})_p\cong M_p$ 
* For $f\in A$, $\tilde{M}(D(f)) \cong M_f$ 
* $\Gamma(X,\tilde{M})=M$

For a ring homomorphism $A\rightarrow B$ with corresponding morphism of spectra $X=SpecA \rightarrow Y=Spec B$ we have 
* The map $M\mapsto \tilde{M}$ gives an excat, fully faithful [[Functor]] from the [[Category]] of $A$-modules to the category of $\mathcal{O}_X$-modules
* For any two $A$-modules $M$ and $N$, $(M\otimes_A N)\tilde{} \cong \tilde{M} \otimes_{\mathcal{O}_X} \tilde{N}$   
* For any family $\{M_i\}$ of $A$-modules, $(\bigoplus M_i)\tilde{} \cong \bigoplus \tilde{M}_i$
* For any $B$-module $N$, $f_*(\tilde{N}) \cong (_AN)\tilde{}$ where $_AN$ means we consider $N$ as an $A$-module
* For any $A$-module $M$, $f^*(\mathcal{M})\cong (M\otimes_A B)\tilde{}$ 