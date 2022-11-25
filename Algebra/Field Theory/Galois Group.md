Let $L:K$ be a [[Field Extension]]. We call the subgroup $Gal(L/K)\subseteq Aut(L)$ ([[Homomorphism#Monomorphisms Epimorphisms and Isomorphisms]]) containing automorphisms $\varphi$ with $\varphi(a) = a \forall a\in K$, the *Galoisgroup* of $L:K$.

Elements of $Gal(L/K)$ have the following properties:
1. if $a\in L$ is the root of $f\in K[t]$, then $\varphi(a)$ is as well 
2. if $L=K(b)$ for some $b\in L$, then $\varphi=id$ $\Leftrightarrow \varphi(b)=b$
3. if $L=K(b)$ for some $b\in L$, then $|Gal(L/K)|$ is the number of roots of $\mu_b$ in $L$.
4. If $L:K$ is quadratic and $CharK \neq 2$, then $Gal(L/K)\cong \mathbb{Z}/2\mathbb{Z}$ 

We have $|Gal(L/K)| \leq [L:K]$ with equality iff $L:K$ is a finite [[Galois Extension]].

For a polynomial $f\in K[X]$ with [[Splitting Field]] $L$, the Galois Group $Gal(L/K)$ is called *Galois Group of f*

For a subgroup $H\subseteq Aut(L)$ we call the field $Fix(H)$ containing all elements $a\in L$  with $\varphi(a) = a \quad \forall \varphi \in H$ the *fixed field* of $H$

if $L:K$ is a [[Galois Extension]] with $G=Gal(L/K)$. then 
1. $K=Fix(G)$
2. For a subgroup $H\subseteq G$ with $Fix(H)=K$ we have $H=G$

#### Fundamental Theorem of Galois Theory

Let $L:K$ be a finite Galois Extension and $G=Gal(L/K)$. Then there is a canonical Bijection between subgroups $H\subseteq G$ and intermediate fields $K\subseteq F \subseteq L$ defined by 

$\alpha : F\mapsto Gal(L/F)\subseteq G$
$\beta :H\mapsto Fix(H)\subseteq L$

For a subgroup $H\subseteq G$, the extension $Fix(H):K$ is a [[Normal Field Extension]] iff $H\subseteq G$ is a [[Normal Subgroup]]. In this case $Gal(F/K) \cong G/H$