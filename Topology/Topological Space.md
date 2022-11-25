A *topological space* is a pair $(X,O)$, where $X$ is a set ([[Sets#Sets]]) and $O$ is a subset of the power set of $X$ satisfying the following axioms

1. $\emptyset,X \in O$ 
2. For any family $\{A_i\}_{i\in I}\subseteq O$, $\bigcup_{i\in I} A_i\in O$
3. Given $A_1,\dots, A_n\in O$, $\bigcap_{i=1}^n A_i \in O$ 

Then $O$ is called a *topology* on $X$, and setes in $O$ are called *open sets*.
If for a subset $C\subseteq X$, the complement $X\setminus C$ is open, $C$ is called closed.

For a point $x\in X$, an open (or closed) set $U\subseteq X$ with $x\in U$  is called an *open neighborhood* (or closed neighborhood) of $x$.

The *discrete topology* on a set $X$ is the topolgy where every subset of $X$ is open.

### Subspaces
Given a subset $A\subseteq X$ of a topological space $X$, $A$ can be given a topology with open sets $S\cap U$ where $U\subseteq X$ is open. We call $A$ a *subspace* with *subspace topology*.

### Interior

Given a subset $A\subseteq X$ of a topological space $X$, the *interior* of $A$, written $int A$ is given by one of the following equivalent definitions 

1. The largest open subset of $X$ contained in $A$
2. The union of all open subsets of $X$ containing $A$

We call $A\setminus (int A)$ the *boundary* of $A$, written $\partial A$. 

### Closure

The *closure* of a subset $A\subseteq X$ of a topological space $X$, written $\bar{A}$  or $clA$ is given by one of the following equivalent definitions

1. The smallest closed subset of $X$ containing $A$
2. The intersection of all closed subsets of $X$ containing $A$

### Covers

An *open (or closed) cover* of a topological space $X$, is a collection of open (or closed) subsets $\{A_i\}_{i\in I}$ s.t. $\bigcup_{i\in I} A_i = X$. We say the $A_i$ *cover* $X$.
A *subcover* of a cover $\{A_i\}_{i\in I}$ is a subfamily of the $A_i$ that still cover $X$.
A *refinement* of a cover $\{A_i\}$ is a cover $\{B_j\}$ if each $A_i$ is contained in some $B_j$

### Basis

A *basis* of a topology on $X$ is a collection of open sets $\mathcal{B}$, s.t. the following two conditions hold
1. Every $x\in X$ is contained in some $B\in \mathcal{B}$. We say $\mathcal{B}$ covers $X$
2. For every $B_1,B_2\in \mathcal{B}$ and every $x\in B_1\cap B_2$ there is some $B_3\in \mathcal{B}$ s.t $B_3\subseteq B_1\cap B_2$ and $x\in B_3$ 

This means that every open set in $X$ is the union of some subfamily of $\mathcal{B}$.  Any collection with this property is said to $\mathcal{B}$ *generate the topology of $X$* (Not every generating family has to be a basis).

A *subbase* of $\mathcal{B}$ of the topology of $X$ is a collection of open sets satisfying any of the following equivalent conditions
1. $\mathcal{B}$ generates the topology of $X$ 
2. The collection of open sets consisting of finite intersections of elements in $\mathcal{B}$ together with $X$ form a basis of the topology of $X$.