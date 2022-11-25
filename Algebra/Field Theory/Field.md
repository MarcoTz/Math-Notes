A *Field* is a set $F$ with two operations $+:F\times F \rightarrow F$ and $\cdot: F\times F \rightarrow F$ s.t. the following holds 

* Associativity: $a+(b+c) = (a+b)+c \quad a\cdot(b\cdot c) = (a\cdot b)\cdot c \quad \forall a,b,c\in F$  
* Commutativity: $a+b = b+a \quad a\cdot b = b\cdot a \quad \forall a,b\in F$
* Identities $\exists 1\in F: 1\cdot a = a\cdot 1 = a \quad \forall a \in F$ and $\exists 0\in F: 0+a = a+0 = a \quad \forall a \in F$
* Inverses: $\forall a \in F \exists a^{-1} \in F: a\cdot a^{-1} = a^{-1}\cdot a = 1$
	$\forall a \in F \exists -a \in F \quad a+(-a) = (-a)=a = 0$
* Distributivity: $a\cdot(b+c) = a\cdot b + a\cdot c$ and $(a+b)\cdot c = a\cdot c + b\cdot c \quad \forall a,b,c\in F$

Alternatively, $(F,+)$ and $(F\setminus \{0\},\cdot)$ are [[Abelian Group]]s and Distributivity holds.
Equivalently, $F$ is a commutative division ring [[Ring#Zero Divisors]].
Note that since fields are special rings, field homomorphisms are just [[Ring Homomorphism]]s between fields.
If $R$ is a commutative integral domain containing a field $K$ and $R$ is a finite-dimensional $K$-vector space, then $R$ is already a field.
Any finite subgroup of the mutiplicative group $K^{*} = K\setminus\{0\}$ is cyclic ([[Abelian Group]]).

