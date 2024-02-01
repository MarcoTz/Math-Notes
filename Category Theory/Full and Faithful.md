A functor $F:\mathcal{A} \rightarrow \mathcal{B}$ is called *faithful* if for each $A,A^{\prime}\in\mathcal{A}$ the map
$$ Mor(A,A^{\prime}) \rightarrow Mor(F(A),F(A^{\prime})$$
$$ f \mapsto F(f)$$
is injective.
$F$ is called *full* if that map is surjective.
Note this definition only makes sense if the collections of morphisms in $\mathcal{A}$ and $\mathcal{B}$ are all sets (that is $\mathcal{A}$ and $\mathcal{B}$ are locally small).
If $F$ is full and faithful, it is called *fully faithful*.