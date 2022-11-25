A *natural transformation* $T$ between two [[Functor]]s $F,G:\mathcal{C}\rightarrow\mathcal{D}$ is a mapping, assigning a morphism $T_X : F(X)\rightarrow G(X)$ to each object $X\in Ob(\mathcal{C})$, s.t. for each morphism $f\in Mor(X,Y)$  in $\mathcal{C}$ the following diagram commutes 

$$ \begin{array}{} F(X) & \xrightarrow{F(f)} & F(Y) \\ 
 \downarrow \small{T_X} & & \downarrow \small{T_Y}\\
 G(X) & \xrightarrow{G(f)} & G(Y)
\end{array}$$
