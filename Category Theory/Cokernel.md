Given a morhpism $f:X\rightarrow Y$  in a [[Category]], the *cokernel* is an object $Q$ with a morhpism $q:Y\rightarrow Q$ s.t. the following diagram commutes 

![[Cokernel Diagram.png]]

Furthermore, this diagram has to be universal, i.e. any other such $q^{\prime}:Y\rightarrow Q^{\prime}$ can be obtained by composing $q$ with a unique morphism $u:Q\rightarrow Q^{\prime}$ .

In the case of [[Group]]s, the cokernel of a [[Group Homomorphism]] $f:G\rightarrow H$ is just $coker(f) = H/im(f)$ if $im(f)$ is a [[Normal Subgroup]] in $H$. Otherwise, replace $im(f)$ with its normalizer. 