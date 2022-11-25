For two pre[[Sheaf]]s $\mathcal{F}$ and $\mathcal{G}$ on $X$, a *morphism* $\varphi : \mathcal{F} \rightarrow \mathcal{G}$ consists of a morphism of objects $\varphi(U) : \mathcal{F}(U) \rightarrow \mathcal{G}(U)$ for each open set $U$ s.t. whenever $V\subseteq U$ we have the following commutative diagram 

$$ \begin{array} \mathcal{F}(Y) &  \xrightarrow{\varphi(U)} & \mathcal{G}(U) \\
\downarrow _{\rho_{UV}} & & \downarrow _{\rho^{\prime}_{UV}} \\ 
\mathcal{F}(V) & \xrightarrow{\varphi(V)} & \mathcal{G}(V)\end{array}$$
An isomorphism is a morphism with two-sided inverse. 
A morhpism of sheaves (not true for presheaves) $\varphi:\mathcal{F}\rightarrow\mathcal{G}$ is an isomorphism iff the induced map $\varphi_P:\mathcal{F}_P\rightarrow \mathcal{G}_P$ is an isomorphism for every $P$.

### kernel, cokernel, image, preimage

Let $\varphi : \mathcal{F} \rightarrow \mathcal{G}$ be a morphism of presheaves. Then we define the following

* The presheaf kernel of $\varphi$: $U\mapsto ker(\varphi(U))$ 
* The presheaf [[Cokernel]]  of $\varphi$: $U\mapsto coker(\varphi(U))$ 
* The presheaf image of $\varphi$: $U\mapsto im (\varphi(U))$ 

All of these are presheaves, and if $\mathcal{F}$ and $\mathcal{G}$ are sheaves, then the presheaf kernel is a sheaf.

If $\varphi$ is a morphism of sheaves, we define the following

* The kernel of $\varphi$, $ker\varphi$, the [[Associated Sheaf]] to the presheaf kernel of $\varphi$ 
* $\varphi$ is injective, if $ker\varphi = 0$, i.e. if the induced map $\varphi(U):\mathcal{F}(U)\rightarrow \mathcal{G}(U)$ is injective for every open set $U$
* The image of $\varphi$, $im\varphi$, the associated sheaf to the presheaf image of $\varphi$. There is a natural injective map $im\varphi \rightarrow \mathcal{G}$ by the unversial property of the associated sheaf
* $\varphi$ is surjective if $im\varphi = \mathcal{G}$.
* A sequence $\dots \mathcal{F}^{i-1} \xrightarrow{\varphi^{i-1}} \mathcal{F}^i \xrightarrow{\varphi^i} \mathcal{F}^{i+1} \rightarrow \dots$ is excat if for all $i$, $ker \varphi^i = im\varphi^{i-1}$ 
* The quotient sheaf of a subsheaf $\mathcal{F}^{\prime}$ of $\mathcal{F}$, denoted $\mathcal{F}/\mathcal{F}^{\prime}$ is the associated sheaf to the presheaf $U\rightarrow \mathcal{F}(U)/\mathcal{F}^{\prime}(U)$. Then for each $P$, $(\mathcal{F}/\mathcal{F}^{\prime})_P = \mathcal{F}_P/\mathcal{F}^{\prime}_P$ 
* The kokernel of $\varphi$, $coker\varphi$ is the sheaf associated to the presheaf cokernel of $\varphi$ 