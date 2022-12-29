For a $n$-manifold ([[Topological Manifold]]) $M$, A *local orientation* at a point $x\in M$ is a generator $\mu_x$ of the infinite cyclic group ([[Abelian Group#Cyclic Groups]]) $H_n(M,M\setminus\{x\})$ ([[Homology]]).

An *orientation* of $M$ is a function $x\mapsto \mu_x$ assigning a local orientation to each $x\in M$, s.t for each $x$ there is a neighborhood $U\cong \mathbb{R}^n$ containing an open ball $B$ (metric induced by the homeomorphism ([[Metric Space]])) with finite radios around $x$, s.t. all local orientations $\mu_y$ at $y\in B$ are the images of the same generator $\mu_B$ or $H_n(M,M\setminus B) \cong H_n(\mathbb{R}^n,\mathbb{R}^n\setminus B)$ under the natural maps $H_n(M,M\setminus B)\rightarrow H_n(M,M\setminus \{y\})$. If such an orientation exists, $M$ is called *orientable*.

Every manifold $M$ has an orientable two-sheeted covering space $\tilde{M}$ ([[Covering Spaces]]).
If $M$ is connected, it is orientable iff $\tilde{M}$ has two components. In particular $M$ is orientable if it is simply connected or $\pi_1(M)$ ([[The Fundamental Group]]) has no subgroup of index $2$.

More generally, an $R$-orientation of a manifold $M$ is a choice of generator of $H_n(M;R)$ for any ring $R$.