A group is a set ([[Sets#Sets]]) $G$ with a binary operation $\cdot : G \times G \rightarrow G$  satisfying the following axioms

a) Associativity: $\forall a,b,c \in G: (a\cdot b) \cdot c = a \cdot (b\cdot c)$ 
b) Identity: $\exists e \in G: \forall a \in G: a\cdot e = e \cdot a = a$ 
c) Inverses: $\forall a\in G \exists a^{-1} \in G : a \cdot a^{-1} = a^{-1} \cdot a = e$

Usually, $a\cdot b$ is written as just $ab$ 
In particular, a group is also a [[Monoid]]

A group is said to be *generated* by elements $g_i \in G$ if each element in $G$ can be expressed as a product of elements $g_i$.
If there are finitely many elements $g_1,\dots,g_n$ generating $G$, we say $G$ is *finitely generated*.

#### Subgroups

A Subset $H\subseteq G$ of a group $G$ is called a subgroup, if $H$ is a group with the product defined on $G$. 
To see that some set $H$ is a subgroup, it suffices to show the following 

* $x,y\in H \Rightarrow xy\in H$ 
* $x\in H \Rightarrow x^{-1}\in H$

#### Order

The *order* of an element $x\in G$ of a group is defined as 

$ord_G(x) = min_{n} x^n = e$ 

If $x^n\neq e$ for all $n$, we say $ord_G(x)=\infty$ 


#### Conjugation

Two subgroups $H_1,H_2$ of $G$ are called *conjugated*, if $gH_1g^{-1} = H_2$ for some $g\in G$.
If $H_1$ and $H_2$ are conjugated, they have the same order

The conjugation $x\mapsto gxg^{-1}$ for any fixed $g\in G$ defined a [[Group Actions]] of $G$ on itself. We call the orbit $Gx$ the *conjugation class* of $x$.