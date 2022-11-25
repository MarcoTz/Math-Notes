A *covering space* of a [[Topological Space]] $X$ is a topological space $\tilde{X}$ with a [[Continous Function]] $p:\tilde{X}\rightarrow X$ satisfying the following condition:

For each $x\in X$, there is a open neighborhood $U$ of $x$ s.t. $p^{-1}(U)$ is a disjoint union of open sets, each of which is homeomorphic ([[Continous Function#Homeomorhpism]]) to $U$ via $p$.

We call such a $U$ *evenly covered*, and the open subsets of $p^{-1}(U)$ mapping homeomorphically to $U$ are called *sheets* over $U$. If $U$ is connected ([[Connectedness]]), the sheets are exactly the connected components of $p^{-1}(U)$. Otherwise, the decomposition of $p^{-1}(U)$ is not necessarily unique.

If $\tilde{X}$ is a covering space of a space $X$, we have the following

* *Path-Lifting Property*: For each path ([[Continous Function#Paths]]) $f:I\rightarrow X$ starting at a point $x_0\in X$ and each $\tilde{x_0}\in p^{-1}(x_0)$, there is a unique path $\tilde{f}:I\rightarrow \tilde{X}$ starting at $\tilde{x_0}$ called the lift of $f$
* *Homotopy Lifting Property*: For each homotopy ([[Homotopy#Homotopy of Paths]]) $f_t:I\rightarrow X$ of paths starting at $x_0$ and each $\tilde{x_0}\in p^{-1}(x_0)$, there is a unique homotopy $\tilde{f_t}:I\rightarrow \tilde{X}$ of paths starting at $\tilde{x_0}$, called *lift of $f_t$* 
* The induced homomorphism ([[The Fundamental Group#Induced Homomorophisms]]) $p_*: \pi_1(\tilde{X},\tilde{x_0})\rightarrow \pi_1(X,x_0)$ is injective. The image subgroup contains all loops at $x_0$ whose lifts are loops at $\tilde{x_0}$. The index ([[Coset]]) of this subgroup is the number of sheets of the covering space.