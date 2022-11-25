For a set $X$ , the symmetric [[Group]] of $X$, denoted $S(X)$ consists of all permutations of elements in $X$, i.e. all [[Function]]s $\sigma: X->X$ that are bijectice, with composition as group law.

If $X=\{x_1,\dots, x_n\}$ is finite, we write $S_n$ for $S(X)$. We can write permutations of $S(n)$ in different ways: 

For a permutation $\sigma\in S(n)$ with $\sigma(k) = i_k$ we write 

$(1\quad 2\quad \dots \quad n)$
$(i_1 \quad i_2 \quad \dots \quad i_n )$

#### Cycles

A *cycle* in $S_n$ is a permutation $\sigma\in S(n)$ s.t. there are  $n_1,\dots,n_m$ with $\sigma(n_i) = \sigma(n_{i+1})$ for each $i<m$ and $\sigma(n_m) = n_1$.
For such a cycle we write $\sigma = (n_1\dots n_m)$ and say $m$ is the length of a cycle.
Two cycles $\sigma_1=(n_1\dots n_m)$ and $\sigma_2=(k_1\dots k_i)$ are called *disjoint* if $n_j\neq k_l$ for any $j,l$. In this case $\sigma_1\sigma_2 = \sigma_2\sigma_1$.

For any element $\sigma \in S_n$, there are disjoint cycles $\sigma_1,\dots, \sigma_m$ s.t. $\sigma = \sigma_1\dots\sigma_n$
This decomposition is unique up to the order of the cycles


#### Cayley's Theorem

Every [[Group]] $G$ is isomorphic to a Subgroup of $S(G)$ 


#### Alternating Group

Ther is a uniuque [[Group Homomorphism]] $sgn : S_n \rightarrow \mathbb{Z}_2$ defined by the length of cycles. A cycle of length $m$ gets mapped to $0$ if $m$ is even and $1$ if $m$ is odd. All other elements are defined by their canonical decomposition 

The Kernel of $sgn$, denoted by $A_n$ is called the alternating group. It is not a [[Simple Group]] for $n\geq 5$.





