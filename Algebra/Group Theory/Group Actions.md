Let $G$ be a [[Group]] and $X\neq \emptyset$ be a Set ([[Sets]]) with permutation group $S(X)$. Then a *Group Action* or *Group Operation* of $G$ on $X$ is a group homomorphism 

$T: G\rightarrow S(X) \quad g \mapsto T(g)=T_g$ 

Equilvalently, we can define a group operation as a [[Function]] $\circ: G\times X \rightarrow X$  satisfying the following conditions

1. $(g_1g_2)\circ x = (g_1 \circ (g_2 \circ x)) \quad \forall g_1,g_2\in G, x\in X$ 
2. $(e\circ x) = x \quad \forall x\in X$


#### Orbits

If $G$ operates on $X$ and $x\in X$ then 

$Gx = \{gx : g\in G\}$ 

is called the *orbit* of $x$ under the operation of $G$.
Group orbits are equivalence classes of the equilvalence [[Relation]] on $X$ defined by 

$x \sim_G x^{\prime} \Leftrightarrow \exists g\in G: x^{\prime} = gx$ 

If the only group orbit of an action is $X$, the action is called *transitive*. This means that for any $x,y\in X$ there is a $g\in G$ s.t. $gx=y$.

#### Stabilizer 

If $G$ operates on $X$ and $x\in X$, we defined the *stabilizer* of $x$ as 

$St_G(x) = \{g\in G | gx=x \}$

This is a subgroup of $G$.
If the stabilizer of all $x\in X$ only contains the identity element $e$, the group action is called *free*. This means that the action does not fix any element of $X$.

#### Orbit-Stabilizer Theorem

If $G$ operates on $X$, then the map $g\mapsto gx$ defines a bijective map $G/St_G(x) \rightarrow Gx$. In particular $|St_G(x)| = |St_G(y)|$ if $x$ and $y$ are in the same orbit.

Using this, we get the orbit-stabilizer theorem if $G$ is finite: 

$|Gx| = |G:St_G(x)| = |G|/|St_G(x)|

#### Orbit Equation

Using the orbit-stabilizer theorem, we get the following equation, if $X$ is finite and $x_1,\dots,x_k$ represent all $G$-orbits of $X$

$|X| = \sum_{i=1}^k |Gx_i| = \sum_{i=1}^k [G:St_G(x_i)]$