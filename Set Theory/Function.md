Also sometimes called map, and function may mean something more specific in some contexts.
A function $f : X \rightarrow Y$ between Sets ([[Sets#Sets]]) $X$ and $Y$ assigns each $x\in X$ an element in $y\in Y$, written $f(x)=y$. $X$ is called *domain* of $f$ and $Y$ its *codomain*.

In [[Sets]], functions can be defined as a [[Relation]] $R$ between $X$ and $Y$ satisfying the relations

* $\forall x \in X \exists y\in Y : (x,y)\in f$
* $(x,y),(x,y^{\prime}) \in f \Rightarrow y=y^{\prime

#### Identity Function 

The function $f:X\rightarrow X$ with $f(x)=x \forall x \in X$ is called the identity function, written $\mathbb{1}_X$ or $id_X$.

#### Preimages

For a function $f:X\rightarrow Y$ and a subset $A\subseteq Y$, the *preimage* of $A$ in $X$ is defined as 

$f^{-1}(A) = \{x\in X | f(x)\in A\}$

If $A = \{y\}$ is a single element, we simply write $f^{-1}(y)$.

#### Function Composition

For two functions $f:X\rightarrow Y$ and $g:Y\rightarrow Z$, the *composition* of $f$ and $g$ is defined as the function 
 
$g\circ f : X\rightarrow Z \quad x\mapsto g(f(x))$

#### Injections, Surjections and Bijections

Let $f:X\rightarrow Y$ be a function, then we say 

* $f$ is an *Injection* or *injective* if $f(x) = f(x^{\prime}) \Rightarrow x=x^{\prime}$
* $f$ is a *Surjection* or *surjective* if $\forall y \in Y \exists x \in X : f(x) = y$ 
* $f$ is a *Bijection* or *bijective* if $f$ is injective and surjective

#### Inverses

For a function $f:X\rightarrow Y$ a function $f^{-1}:Y\rightarrow X$ is called 

* *Left Inverse* if $f^{-1}\circ f = \mathbb{1}_Y$ 
* *Right Inverse* if $f\circ f^{-1} = \mathbb{1}_X$
* *Inverse* or two-sided inverse, if it is both a left inverse and a right inverse

We have the following equivalences: 

* $f$ has a left inverse $\Leftrightarrow$ $f$ is injective
* $f$ has a right inverse $\Leftrightarrow$ $f$ is surjective 
* $f$ has a two-sided inverse $\Leftrightarrow$ $f$ is bijective

Inverses for $f$ are usually denoted by $f^{-1}$ , not to be confused with the notation for [[#Preimages]]

### Restriction

Given a function $f:X\rightarrow Y$ and a subsets $A\subseteq X$, the *restriction* of $f$ to $A$, is the map $f|_A: A\rightarrow Y$ defined by $f|_A(a) = f(a) \forall a\in A$.

### Graphs

The *graph* of a function $f:X\rightarrow Y$ is the subset of $X\times Y$ containing elements $(x,f(x))$

