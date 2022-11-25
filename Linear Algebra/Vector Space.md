A *Vector Space* over a [[Field]] $K$ is an [[Abelian Group]] $V$ with a binary operation $K\times V \rightarrow V$, often called *scalar multiplication* s.t. the following conditions hold 

1. $a(bv) = (ab)v \quad \forall a,b\in K, v\in V$
2. $1v = v \quad \forall v \in V$
3. $a(u+v) = au + av$ and $(a+b)v = av + bv \quad \forall a,b\in K, v,u\in V$

Elements in $V$ are called *vectors* and elements in $K$ *scalars*.


#### Subspace 

A subset $U\subseteq V$ is called a *linear subspace* if $U$ is a $K$-Vector space with the addition and scalar mutliplication of $V$.
A subspace of dimension ([[#Basis and Dimension]]) $n-1$ in a vector space of dimension $n$ is called as *hyperplane*.
A subspace of dimension $1$ is called a *line*, and a subspace of dimension $2$ is called a *plane*.

#### Linear Combinations 

For vectors $v_1,\dots,v_n\in  V$ and $a_1,\dots,a_n$, the sum $a_1v_1+\dots+a_nv_n$ is called a *linear combination* of $v_1,\dots,v_n$ 

#### Linear Independence

Vectors $v_1,\dots, v_n\in V$ are called *linearly independent*, if for any linear combination $v=a_1v_1+\dots+a_nv_n$ with $v=0$ we have $a_1=\dots=a_n=0$.
If $v_1,\dots,v_n$ are not linearly independent, we say they are *linearly dependent*.

#### Span

Given Vectors $v_1,\dots,v_n\in V$, we call the set of all linear combinations of $v_1,\dots,v_n$ the *span* of those vectors, writen $span(v_1,\dots,v_n)$ or $\langle v_1,\dots,v_n\rangle$.
The span of a set of vectors is a linear subspace


#### Basis and Dimension

Given a vector space $V$ with vectors $v_1,\dots,v_n$ s.t. $span(v_1,\dots,v_n)=V$ and $v_1,\dots,v_n$ are linearly independent, the set $v_1,\dots,v_n$ is called a *basis* of $V$.
In this case, $n$ is called the *Dimension* of $V$,  denoted $dimV$. This is well defined, as any two bases of $V$ have the same number of elements.
Any $K$-Vector Space with dimension $n$ is isomorphic to $K^n$.
