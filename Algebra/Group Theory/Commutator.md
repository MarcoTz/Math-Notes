Let $G$ be a [[Group]] with elements $x,y\in G$, then the *commutator* of $x$ and $y$ is defined as

$[x,y] = xyx^{-1}y^{-1}$ 

We have $[x,y]^{-1} = [y,x]$ and if $x$ and $y$ commute $[x,y] = e$.

The *commutator group* of a group $G$, denoted by $[G,G]$ is the Subgroup containing all commutators of elements in $G$.
If $G$ is abelian $[G,G] = \{e\}$

We define the *higher commutator groups* $G^{(n)}$ as $G^{(n)} = [G^{(n-1)},G^{(n-1)}]$.
Then for any [[Group Homomorphism]] $\varphi : G\rightarrow H$, $\varphi(G^{(n)}) \subseteq H^{(n)}$ with equality if $\varphi$ is an Epimorphism ([[Homomorphism#Monomorphisms Epimorphisms and Isomorphisms]]).

### Abelianization

For any group $G$, $[G,G]$ is a [[Normal Subgroup]] of $G$, and $G/[G,G]$ is an [[Abelian Group]], called the *abelianization of $G$.