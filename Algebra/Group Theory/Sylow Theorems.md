#### p-primary components

For a prime number $p$ and an [[Abelian Group]] $G$, the set

$G(p) = \{g\in G| \exists l\in \mathbb{N}: g^{p^l}=e\}$

is a subgroup called *p-primary component* of the [[Group]] $G$.
If $|G| = p_1^{l_1}\dots p_k^{l_k}$, then $G \cong G(p_1)\dots G(p_k)$.

#### Sylow-Groups

If $G$ is a group with order $|G|=p^km$ where $p$ is prime and $m$ is not a multiple of $p$, then any subgroup $H\subseteq G$ with $|H| = p^k$ is called *p-Sylow group*.

####  Sylow Theorems

For a finite group $G$ with $|G| = p^km$, $p$ prime and $gcd(p,m)=1$ we have 

1. There is a $p$-Sylowgroup $H\subseteq G$
2. If $H^{\prime}\subseteq G$ is a subgroup of order $|H| = p^n$ with $n\leq k$ and $H$ a $p$-Sylowgroup, then $H$ and $H^{\prime}$ are conjugated.
	In particular, any two $p$-Sylowgroups are conjugated
3. The number of $p$-Sylowgroups divides $m$ and has the form $1+np$ with $n\geq$ 0 