Let $A$ be a commutative [[Ring]] and $B$ an $A$-[[Algebra]]. Then the [[Module]] of *relative differential forms of $B$ over $A$* is a $B$-module $\Omega_{B/A}$ with a [[Derivation]] $d:B\rightarrow \Omega_{B/A}$ satisfying the following universal property:
For any $B$-module $M$ and any $A$-derivation $d^{\prime}: B\rightarrow M$, there exists a unique $B$-module homomorphism $f:\Omega_{B/A}\rightarrow M$ s.t. $d^{\prime} = f\circ d$

$\Omega_{B/A}$ exists and is unique up to isomporphism. It is generated as a $B$-module by $\{db|b\in B\}$ 

For an $A$-algebra $B$ with diagonal homomorphism $f:B\otimes_A B\rightarrow B \quad b\otimes b^{\prime} \mapsto bb^{\prime}$ and $I=kerf$, $I/I^2$ is a $B$-module by left multiplication and with $d:B\rightarrow I/I^2 \quad db=1\otimes b-b\otimes 1$ a module of relative differentials for $B/A$.

For two $A$-algebras $B$ and $A^{\prime}$, let $B^{\prime} = B\otimes_A A^{\prime}$. Then $\Omega_{B^{\prime}/A^{\prime}}\cong \Omega_{B/A}\otimes_B B^{\prime}$ and for any multiplicative system $S$ in $B$, we have $\Omega_{S^{-1}B/A}\cong S^{-1}\Omega_{B/A^{\prime}}$ 

Let $K$ be a finitely generated [[Field Extension]] of a [[Field]] $k$. Then $dim_K \Omega_{K/k} \geq trdeg K/k$ ([[Transcendence Degree]]) with equality iff $K$ is [[Separably generated]] over $k$.
