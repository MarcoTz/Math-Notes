A *natural transformation* $T$ between two [[Functor]]s $F,G:\mathcal{C}\rightarrow\mathcal{D}$ is a mapping, assigning a morphism $T_X : F(X)\rightarrow G(X)$ to each object $X\in Ob(\mathcal{C})$, s.t. for each morphism $f\in Mor(X,Y)$  in $\mathcal{C}$ the following diagram commutes 

$$ \begin{array}{} F(X) & \xrightarrow{F(f)} & F(Y) \\ 
 \downarrow \small{T_X} & & \downarrow \small{T_Y}\\
 G(X) & \xrightarrow{G(f)} & G(Y)
\end{array}$$
The morphisms $T_X$ are called *components* of $T$.
For any two categories $\mathcal{A}$ and $\mathcal{B}$, the functor category $[\mathcal{A},\mathcal{B}]$ from $\mathcal{A}$ to $\mathcal{B}$ is the category with objects functors $\mathcal{A}\rightarrow\mathcal{B}$ and maps natural transformations. 
If $T$ is a natural transformation between functors $\mathcal{A}\rightarrow\mathcal{B}$, that is an isomorphism in $[\mathcal{A},\mathcal{B}]$, it is called a *natural transformation*
A natural transformation $T$ between $F,G:\mathcal{A}\rightarrow\mathcal{B}$ is a natural isomorphism if and only if $T_A  : F(A)\rightarrow G(A)$ is an isomorphism for all $A\in\mathcal{A}$.
If $F$ and $G$ are naturally isomorphic functors, we say $F(A)\cong G(A)$ *naturally in $A$.