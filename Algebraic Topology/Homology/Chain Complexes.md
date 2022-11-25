Given an algebraic object $X$ (e.g. a [[Topological Space]]) and a sequence of [[Abelian Group]]s $C_0,C_1,\dots$ called *chain groups* with [[Group Homomorphism]]s $\partial_n:C_n \rightarrow C_{n-1}$ with the condition that $\partial_n \circ \partial_{n+1} = 0\forall n$, we say the $C_n,\partial_n$ define a *chain complex*. The homomorphisms $\partial_n$ are called *boundary maps* and we denote the chain complex by a diagram ([[Diagram]])

$$ \dots \xrightarrow{\partial_{n+1}} C_n \xrightarrow{\partial_n} C_{n-1} \xrightarrow{\partial_{n-1}} \xrightarrow{n-2} \dots \xrightarrow{\partial_2} C_1 \xrightarrow{\partial_1} C_0 \xrightarrow{\partial_0} 0$$
The condition $\partial_n\circ \partial_{n+1}=0$ is equivalent to $im(\partial_{n+1})\subseteq ker(\partial_n)$.
We usually only write $\partial$ for $\partial_n$, when the index is not relevant.
Elements in $im(\partial_{n+1})$ are called *boundaries* and elements of $ker(\partial_n)$ are called *cycles*.
Elements of $C_n$ are called *n-chains*.
From the condition, we see that all cycles are also boundaries.

### Chain maps

Given two chain complexes $C_n$ and $D_n$ and a map $f:C_n\rightarrow D_n$ for each $n$ (technically the domain of $f$ is the disjoint union of all $C_n$ and the codomain the disjoint union of all $D_n$), $f$ is called $ *chain map*, if $f\partial = \partial f$.
In other words, the following diagram is commutative

$$ \begin{array}{cccccc} \dots & \xrightarrow{\partial} & C_n & \xrightarrow{\partial} & C_{n-1} & \dots \\
\\ \dots & & \downarrow \small{f} & & \downarrow \small{f} & \dots\\
\dots & \xrightarrow{\partial} & D_n & \xrightarrow{\partial} & D_{n-1} & \dots
\end{array}$$
For example, a [[Continous Function]] $f:X\rightarrow Y$ induces a chain map on [[Singular Homology]] by composition with singular simplices.
Chain maps induce homomorphisms $f_*$ on [[Homology]].

A *chain homotopy* $D:f\rightarrow g$ between chain maps $f$ and $g$ is a sequence of homomorphims $P^k: C_k \rightarrow D_{k-1}$ with $f-g = P\partial + \partial P$. If a chain homotopy between $f$ and $g$ exists, we say they are *chain homotopic*.

### Cochain Complex

Given a chain complex with chain groups $C_n$ and boundary maps $\partial$, applying the operator $Hom(-,G)$ to $C_n$, i.e. replacing $C_n$ by the dual group of homomorphisms $C_n\rightarrow G$ for a fixed abelian group $G$ and replacing the boundary maps $\partial$ with their dual maps $\partial^*$, written $\delta$, defined as the composition $\delta(\varphi) = \varphi\circ \delta$, gives a new chain complex called the *cochain complex* of the original one.
We write the chain groups $Hom(C_n,G)$ as $C_n^*$, then $\delta$ maps $C_n$ to $C_{n+1}$.