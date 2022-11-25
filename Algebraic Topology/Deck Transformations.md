Given a covering space $\tilde{X}$ ([[Covering Spaces]]) of a [[Topological Space]] $X$, an automorphism ([[Homomorphism#Monomorphisms Epimorphisms and Isomorphisms]]]) $\tilde{X}\rightarrow \tilde{X}$ is called a *deck transformation*.
These form a group $G(\tilde{X})$ under composition.
If $\tilde{X}$ is path-connected ([[Path Connectedness]]), by the path lifting-property, a deck transformation is completely determined by where it sends a single point.

### Normal Covering Spaces
A covering space is called *normal*, if for each $x\in X$ and any two lifts $\tilde{x_0}$ and $\tilde{x_1}$ there is a deck transformation sending $\tilde{x_0}$ to $\tilde{x_1}$,
We can classify normal covering spaces the following way

Let $p:(\tilde{X},\tilde{x_0})\rightarrow (X,x_0)$ be a path-connected covering space of a path-connected, locally path-connected space $X$ and let $H$ be the subgroup $p_*(\pi_1(\tilde{X},\tilde{x_0}))\subseteq \pi_1(X,x_0)$. Then 
1. $\tilde{X}$ is normal iff $H$ is normal ([[Normal Subgroup]])
2. $G(\tilde{X})\cong N(H)/H$ where $N(H)$ is the normalizer of $H$
In particular $G(\tilde{X})\cong \pi_1(X,x_0)/H$ if $\tilde{X}$ is a normal covering.
So for the universal cover of $X$ we have $G(\tilde{X})\cong \pi_1(X)$
