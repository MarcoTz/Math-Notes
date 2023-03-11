Let $A$ be a commutative [[Ring]] and $I$ an [[Ideal]] of $A$. Then we have a natural sequence $\dots \rightarrow A/I^3 \rightarrow A/I^2 \rightarrow A/I$ which makes $(A/I^n)$ into an inverse system ([[Inverse Limit]]. The direct limit of this system $\hat{A} = \underleftarrow{\lim} A/I^n$ is then called the *completion of $A$ with respect to $I$* or the *$I$-adic completion of $A$*.
There are natural maps $A\rightarrow A/I^n$ for each $n$ which give a homomorphism $A\rightarrow \hat{A}$.

$\hat{A}$ has the following properties 
* $\hat{I} = \underleftarrow{\lim} I/I^n$ is an ideal of $\hat{A}$ and $\hat{I}^n = I^n \hat{A}$, $\hat{A}/\hat{I}^n \cong A/I^n$ for any $n$
* if $M$ is a finitely generated $A$-[[Module]], $\hat{M} \cong M \otimes_A \hat{A}$
* the functor $M\mapsto \hat{M}$ is an exact functor on the category of finitely generated $A$-modules
* $\hat{A}$ is a [[Noetherian Ring]]
* if $(M_n)$ is an inverse system of $A$-modules s.t. each $M_n$ is a finitely generated $A/I^n$-module, s.t. each $\varphi_{n^{\prime}n}:M_{n^{\prime}} \rightarrow M_n$ is surjective and $ker\varphi_{n^{\prime}n} = I^nM_{n^{\prime}}$, then $M=\underleftarrow{\lim} M_n$ is a finitely generated $\hat{A}$-module with $M_n\cong M/I^nM$ for each $n$