A *affine variety* is a irreducible ([[Irreducible Sets]]), closed subset of $\mathbb{A}^n$ in the [[Zariski Topology]]. Sometimes *variety* is also used for reducible sets. Open subsets of affine varieties are called *quasi-affine varieties*. For any ideal $I$ of $k[x_1,\dots,x_n]$ all points $P$ of $\mathbb{A}^n$ s.t. $f(P)=0$ for all $f\in I$ is called the variety of $I$, denoted $Z(I)$.

### Ideals of Varieties

The [[Ideal]] of an affine variety $Y$ is defined as $I(A) = \{f\in k[x_1,\dots,x_n] : f(P)=0\forall P\in Y\}$. 
Such ideals have the following properties

* $T_1\subseteq T_2\subseteq k[x_1,\dots,x_n] \Rightarrow Z(T_2)\subseteq Z(T_1)$ 
* $Y_1\subseteq Y_2\subseteq \mathbb{A}^n \Rightarrow I(Y_2)\subseteq I(Y_1)$ 
* $I(Y_1\cup Y_2) = I(Y_1)\cup I(Y_2)$
* $Z(I(Y)) = cl(Y)$ 

By [[Hilbert's Nullstellensatz]], there is a 1-1 correspondence between radical ideals in $k[x_1,\dots,x_n]$ (i.e. ideals $a$ with $\sqrt{a}=a$) and varieties, and a 1-1 correspondence between maximal ideals and points of $\mathbb{A}^n$.


### Coordinate ring

The *coordinate ring* $A(Y)$ of an affine variety or simply Zariski-closed set $Y \subseteq \mathbb{A}^n$ is the ring $K[x_1,\dots,x_n]/I(Y)$. 
This ring is an integral domain ([[Ring#Zero Divisors]]) and a finitely generated $k$-algebra ([[Algebra]])

### Dimension

The dimension of an affine or quasi-affine variety $Y$ is defined as the supremum $n$ s.t. there exists a chain $Z_0\subset Z_1 \subset \dots \subset Z_n$ of distinct irreducible closed subsets of $Y$.
The dimension of any Zariski-closed set (in particular of an affine variety) is equal to the Krull dimension ([[Ring#Krull Dimension]]) of its coordinate ring $A(Y)$.
For a quasi-affine variety $Y$ we have $dim(Y) = dim(cl(Y))$
The dimension of a variety $Y\subseteq \mathbb{A}^{n}$ is $n-1$ iff $Y=V(f)$ for a single polynomial $f$. 