A *ringed space* is a pair $(X,\mathcal{O}_X)$ consisting of a [[Topological Space]] $X$ and a [[Sheaf]] of [[Ring]]s $\mathcal{O}_X$ on $X$.

A morhpism of ringed spaces $(f,f^{\#}):(X,\mathcal{O}_X)\rightarrow (Y,\mathcal{O}_Y)$ is a pair with $f:X\rightarrow Y$ a [[Continous Function]] and $f^{\#}:\mathcal{O}_Y\rightarrow \mathcal{O}_X$ a map of sheaves.

A ringed space $(X,\mathcal{O}_X)$ is called *locally ringed space*, if the stalk $\mathcal{O}_{X,P}$ is a [[Local Ring]] for each $P$.

A morhpism of locally ringed spaces is a morphism of ringed spaces, $(f,f^{\#})$ s.t. the induced map $f^{\#}_P:\mathcal{O}_{Y,f(P)}\rightarrow \mathcal{O}_{X,P}$ is a local homomorphism of local rings. This induced map is induced by the following 
$\mathcal{O}_{Y,f(P)} = \lim_V \mathcal{O}_Y(V) \rightarrow \lim_V \mathcal{O}_X(f^{-1}V)$ 