A *Functor* $F$ between two categories ([[Category]]) $\mathcal{C}$ and $\mathcal{D}$ is a mapping, assigning each $X\in Ob(\mathbb{C})$ a $F(X)\in Ob(\mathcal{D})$ and each morphism $f\in Mor_{\mathcal{C}}(X,Y)$ a morphism $F(f)$ in $\mathcal{D}$ .
$F(f)$ is either a morphism in $Mor_{\mathcal{D}}(F(X),F(Y)$, in which case $F$ is called *covariant*, or a morphism in $Mor_{\mathcal{D}}(F(Y),F(X))$, in which case $F$ is called *contravariant*.
A functor must satisfy the following properties

1. $F(\mathbb{1}_{X}) = \mathbb{1}_{F(X)}$ for every $X\in Ob(\mathcal{C})$
2. If $F$ is covariant, $F(f\circ g) = F(f)\circ F(g)$ for each $f\in Mor(X,Y),g\in Mor(F(X),F(Y))$ 
    If $F$ is contravariant $F(f\circ g) = F(g)\circ F(f)$ for each $f\in Mor(X,Y), g\in Mor(F(Y),F(X))$

A contravariant functor $\mathcal{A}\rightarrow \mathcal{B}$ is the same as a covariant functor $\mathcal{A}^{op}\rightarrow\mathcal{B}$ 
