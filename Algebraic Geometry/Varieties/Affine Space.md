An *affine space* $A$ is a set ([[Sets]]) with a [[Vector Space]] $\overrightarrow{A}$ and a [[Group Actions]] of the additive group of $\overrightarrow{A}$ on $A$, that is transitive and free ([[Group Actions#Orbits]],[[Group Actions#Stabilizer]]). 
In other words, there is a map $A\times \overrightarrow{A} \rightarrow A \quad (a,v)\mapsto a+v$ with the following properties 

1. Right identity: $\forall a\in A : a+0 = a$ 
2. Associativity: $\forall v,w\in \overrightarrow{A}, (a+v)+w=a+(v+w)$ 
3. Free and Transitive: $\forall a\in A$ the map $\overrightarrow{A}\rightarrow A \quad v\mapsto a+v$ is bijective ([[Function#Injections Surjections and Bijections]])

Intuitively, an affine space is a vector space, where we "forget" the the origin.
In particular, given an affine space $A$ with vector space $V$, we can view elements of $A$ as elements of $V$ with a fixed vector $v\in V$ added to them, where we consider $v$ to be the origin of $A$. Then $V$ is also an affine space over itself, with origin $0
The *dimension* of an affine space $A$ is the dimension of its associated vector space ([[Vector Space#Basis and Dimension]]).
By considering an affine space as a vector space, we can use terminology from vector spaces (e.g. *lines*, *planes*, *Quotient Space*, etc.) for affine spaces.

If $K$ is a field, we call the vector space $K^n$, considered as an affine space, the *affine $n$-space over $K$*, denoted by $\mathbb{A}^n_K$ or $\mathbb{A}^n$ if $K$ is clear from context. 

### Affine subspaces 

An *affine subspace* $B$ of an affine space $A$ is an affine space that is a subset of $A$ s.t. given some $a\in B$, the set $\{b-a|b\in B\}$ is a linear subspace of $\overrightarrow{A}$.
We can interpret this as a linear subspace of $\overrightarrow{A}$ with some constant vector added to it.

### Affine maps

Given two affine spaces $A$ and $B$ with associated vector spaces $\overrightarrow{A}$ and $\overrightarrow{B}$ an *affine homomorphism* or *affine map* is a [[Function]] $f:A\rightarrow B$ s.t. $\overrightarrow{f}: \overrightarrow{A}\rightarrow \overrightarrow{B}$  defined by $b-a\mapsto f(b)-f(a)$ is a [[Linear Map]].
If we view $A$ and $B$ as vector spaces with a constant vector added, this map has the form $Mx+b$ where $M$ is the usual [[Matrix]] representing a linear map, and $b$ is a constant.

Affine maps are [[Homomorphism]]s of affine spaces