
Let $0\rightarrow G\rightarrow H \rightarrow K\rightarrow 0$ be a short [[Exact Sequence]] of [[Abelian Group]]s, applying the covariant [[Functor]] $Hom(C_n(X),-)$ (where $C_n(X)$ is a chain group ([[Chain Complexes]])), gives an exact sequence 

$$ 0 \rightarrow C^n(X;G) \rightarrow C^n(X;G) \rightarrow C^n(X;K) \rightarrow 0$$ 
For differing $n$, this gives an exact sequence of chain complexes with associated long exact sequence 

$$ \dots \rightarrow H^n(X;G) \rightarrow H^n(X;H) \rightarrow H^n(X;K) \rightarrow H^{n+1}(X;G) \rightarrow \dots$$ 
The map $\beta: H^n(X;K)\rightarrow H^{n+1}(X;G)$ is called *Bockstein homomorphism*.

In the special case starting with $0\rightarrow \mathbb{Z} \xrightarrow{m} \mathbb{Z} \rightarrow \mathbb{Z}_m \rightarrow 0$ we get the following diagram with commutative triangle and we have $\beta(a\smile b) = \beta(a)\smile b + (-1)^{|a|}a \smile \beta(b)$ ([[Cup Product]])
![[Bockstein Diagram.png]]
