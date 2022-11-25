

Let $C$ be a chain complex of free abelian groups ([[Free Groups]],[[Abelian Group]]), then the [[cohomology]] groups $H^n(C;G)$ of the cochain complex $Hom(C_n;G)$ are determined by the following split exact sequences ([[Exact Sequence#Splitting Lemma]])

$$ 0 \rightarrow Ext(H_{n-1}(C),G)\rightarrow H^n(C;G) \xrightarrow{h} Hom(H_n(C),G)\rightarrow 0$$
This means in particular, that the cohomology groups $H^n$ are uniquely determined by $G$ and the homology groups $H_n$.

Here $h$ is the map defined as follows. Given a class in $H^n(C;G)$, represented by $\varphi$ with $\delta\varphi = 0$. Restricting $\varphi$ to the cycles $ker\partial$ gives a homomorphism $\varphi_0:ker\partial\rightarrow G$ which then induces a quotient homomorhpism $\bar{\varphi}:Ker\partial/Im\partial \rightarrow G\in Hom(H_n(C),G)$. So we define $h$ as $h([\varphi]) = \bar{\varphi}$.

The group $Ext(H_{n-1}(C),G)$ is the cohomology group $H^1(F;G)$ where $F$ is a free resolution of $H_{n-1}(C)$ ([[Free Groups#Free resolution]]) and it has the following properties 

* $Ext(H\oplus H^{\prime})\cong Ext(H,G) \oplus Ext(H^{\prime},G)$ 
* $Ext(H,G)=0$ if $H$ is free
* $Ext(\mathbb{Z}_n,G) \cong G/nG$ 

When $H_n$ and $H_{n-1}$ are finitely generated with torsion subgroups $T_n\subseteq H_n$ and $T_{n-1}\subseteq H_{n-1}$, this theorem gives 

$$ H^n(C,\mathbb{Z}) \cong (H_n/T_n)\oplus T_{n-1} $$