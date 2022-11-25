Sets are objects in ZF(C). In modern mathematics, this is almost the only kind of set that is used, though there are other ways to formalize the idea of a set.

##### Subsets
A subset $A$ of a set $X$ is a set s.t. for any $a\in A$ we have $a\in X$. We write $A\subseteq X$.
We say two subsets $A,B\subseteq X$ are *disjoint*, if $A\cap B = \emptyset$.

#### Order 

The *order* or *cardinality* of a set is the number of elements it contains, written $|X|$.

#### Cartesian Product 
The Cartesian Product of two sets $A$ and $B$, written $A\times B$ , is the set of all ordered pairs $(a,b)$ with $a\in A$ and $b\in B$ 

$\forall a\in A, b\in B \Leftrightarrow (a,b)\in A\times B$

#### Zermelo-Fraenkel Set Theory

The following axioms characterize sets used in modern mathematics.

1. Axiom of Extensionality
	Sets are Equal if they have the same elements
    $\forall X \forall Y (\forall z\in X \Leftrightarrow z\in Y) \Rightarrow X=Y$
2. Axiom of Regularity
	Every nonempty set $X$ contains a member $y$,  s.t. $X$ and $y$ are disjoint 
    $\forall X ( X\neq \emptyset \Rightarrow \exists y\in X : y\cap X = \emptyset)$
3. Axiom Schema of Specification
	Set builder notation can be used and always speficies a well defined set (possibly empty)
	Given a formula $\varphi$ in ZF(C) using free variables $x,z,w_1,\dots,w_n$ then 
	$\forall z, w_1,\dots,w_n \exists y \forall x (x\in y \Leftrightarrow (( x\in z) \vee \varphi(x,w_1,\dots,w_n,z))$
	Note that this can only construct subsets, not any general set
4. Axiom of Pairing
	If $x$ and $y$ are sets, there exists a set with $x$ and $y$ as elements
	$\forall x \forall y \exists z ( x\in z) \vee (y\in z)$
5. Axiom of Union
	The Union over the elements of a set exists
	$\forall \mathcal{F} \exists A \forall Y \forall x ((x\in Y \vee Y \in \mathcal{F}) \Rightarrow x\in A)$
6. Axiom Schema of Replacement
	The image of a set under any definable function will also be in a set
	Given a formula $\varphi$ in ZF(C) with free variables $x,y,A,w_1,\dots,w_n$ then
	$\forall A, w_1,\dots, w_n (\forall x ( x\in A \Rightarrow \exists ! y \varphi) \Rightarrow \exists B \forall x ( x\in A \Rightarrow \exists y (y\in B\vee \varphi)))$
7. Axiom of Infinity
	There exists a set with infinitely many members
	$\exists X (\exists e (\forall z \not (z\in e)) \vee e\in X \vee \forall y (y\in X \Rightarrow S(y)\in X))$, where $S(w) = w\cup \{w\}$ for any set $w$
8. Axiom of Power Set
	For every set, there is a power set, i.e. a set that contains every subset as members
	$\forall x \exists y \forall z\subseteq x \Rightarrow z\in y$
9. Well-Ordering Theorem
	For any set $X$, there is a binary relation $R$ which well-orders $X$ (see [[Order]])
	$\forall X\exists R : R$ well-orders $X$
	

In particular, ZF set theory only contains sets, so all other objects, for example [[Function]]s or Numbers, are just sets.

##### Axiom of Choice

$\forall X ( \emptyset \notin X \Rightarrow f:X\rightarrow \bigcup X \forall A \in X (f(A)\in A)$

In other words: For any set $X$ of nonempty sets, there exists a choice function $f$ that maps each set in $X$ to a single element of it.
For finite sets $X$, this follows from the other axioms, but for infinite sets, it is indepentent of them. Therefore it is not needed for a consistent set theory, but it is still used most of the time, as it is important for many results.

The axiom of choice is equivalent to a number of other results:
* Tarski's theorem of choice: For every infinite set $A$, there is a Bijection ([[ Function#Injections Surjections and Bijections]]) between sets $A$ and $A\times A$ ([[#Cartesian Product]])
* Every [[Vector Space]] has a Basis
* Every Connected [[Graph]] has a spanning tree
