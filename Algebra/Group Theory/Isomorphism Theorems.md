For two subgroups $H_1, H_2$ of a [[group]] $G$, we define 

$H_1H_2 = \{h_1h_2\in G | h_1\in H_1, h_2\in H_2\}$

In general, this is not a subgroup

#### 1. Isomorphism Theorem

Let $G$ be a group with [[Normal Subgroup]] $N$ and $\rho: G\rightarrow G/N$ the canonical homomorphism (see [[Quotient Group]]) and $H$ any subgroup of $G$. Then 

1. $HN=\rho^{-1}(\rho(H))$ and in particular, $HN$ is a subgroup of $G$
2. $N$ is a normal subgroup of $HN$ and $\rho(HN) \cong  HN/N$
3. $H\cap N$ is a normal subgroup of $H$ and $\rho(H) \cong H/(H\cap N)$
4. The map $g(H\cap N) \mapsto gN \forall g\in H$ defines an isomorphism $H/(H\cap N) \cong HN/N$

#### 2. Isomorphism Theorem

Let $N_1,N_2$ be normal subgroups of a group $G$ with $N_1\subseteq N_2$. Then $gN_1 \mapsto gN_2$ defines an epimorpism ([[Homomorphism#Monomorphisms Epimorphisms and Isomorphisms]]) $\varphi G/N_1 \rightarrow G/N_2$ with $ker\varphi = N_2/N_1$. In particular, $\varphi$ defines an isomorphism

$(G/N_1)/(N_2/N_1) \cong G/N_2$