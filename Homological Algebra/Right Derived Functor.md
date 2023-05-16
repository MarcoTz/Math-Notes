Let $\mathfrak{U}$ be an [[Abelian Category]] with enough injectives ([[Injective Object]]) and $F:\mathfrak{U}\rightarrow \mathfrak{B}$ a covariant left exact functor ([[Exact Functor]]). Then the *right derived functors* $R^iF$, $i\geq 0$ are defined as follows.
For each object $A$ of $\mathfrak{U}$ let $I^{\prime}_A$ be a fixed injective resolution of $A$, then $R^iF(A) = h^i(F(I^{\prime}))$ ([[Cohomology Object]])

The  right derived functors have the following properties

* for each $i\geq 0$, $R^iF$ is additive ([[Additive Functor]]) and independent (up to natural isomorphisms) of choices of injective resolutions made
* There is a natural isomorphism $F\cong R^0F$
* For each short [[Exact Sequence]] $0\rightarrow A^{\prime} \rightarrow A \rightarrow A^{\prime\prime} \rightarrow 0$ and each $i\geq 0$, there is a natural morphism $\delta^i: F^iF(A^{\prime\prime} \rightarrow R^{i+1}F(A^{\prime})$ s.t. there is a long exact sequence 
 $$ \dots R^iF(A^{\prime}) \rightarrow R^iF(A) \rightarrow R^iF(A^{\prime\prime}) \xrightarrow{\delta^I} R^{i+1}F(A^{\prime}) \rightarrow R^{i+1}F(A) \rightarrow \dots $$
 * Given a morphism of of two exact sequences $0\rightarrow A^{\prime} \rightarrow A \rightarrow A^{\prime\prime} \rightarrow 0$ and $0\rightarrow B^{\prime} \rightarrow B \rightarrow B^{\prime\prime} \rightarrow 0$, the $\delta$ give a commutative diagram ![[RIght derived functor diagram.png]]
 * For each injective object $I$ of $\mathfrak{U}$ and each $i>0$ we have $R^iF(I) = 0$ 