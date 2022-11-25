A family of [[Continous Function]]s $f_t:X\rightarrow Y$ with $t\in I$ s.t. the associated map $F:X\times I \rightarrow Y$ with $F(t,x)=f_t(x)$ is continous, is called a *homotopy*. We say the maps $f_0$ and $f_1$ are *homotopic*, written $f_0 \simeq f_1$.

### Relative Homotopy

A homotopy $f_t:X\rightarrow Y$ s.t the restriction $f_t|_A$ to a subspace ([[Topological Space#Subspaces]]) $A\subseteq X$ is the identity for all $t$, is called a *homotopy relative to A*, often written as *homotopy rel A*.

### Homotopy Equivalence

A map $f:X\rightarrow Y$ is called a *homotopy equivalence*, if there is a map $g:Y\rightarrow X$ s.t. $f\circ g \simeq \mathbb{1}$ and $g\circ f \simeq \mathbb{1}$. We say $X$ and $Y$ are *homotopy equivalent* or have the same *homotopy type* and write $X\simeq Y$.

Homotopy equivalence is a weaker condition than being homeomorphic ([[Continous Function#Homeomorhpism]]).

The induced homomorphisms ([[The Fundamental Group#Induced Homomorophisms]]) od a homotopy equivalence are all isomorphisms.

### Nullhomotopic

A map $f:X\rightarrow Y$ is called *nullhomotopic*, if it is homotopic to a constant map. 
If the identity map of a space $X$ is nullhomotopic, $X$ is called *contractible*.

### Collapsing Subspaces 

If $(X,A)$ is a CW-pair ([[Cell Complexes]]) and $A$ is a contractible subcomplex, then the quotient map $X\rightarrow X/A$ is a homotopy equivalence


### Homotopy Equivalence Condition

A map $f:X\rightarrow Y$ is a homotopy equivalence iff $X$ is a deformation retract of the mapping cylinder $M_f$. So two spaces are homotopy equivalent, iff there is a space containing $X$ and $Y$ as deformation retracts

#### Homotopy of Paths 

Given two paths $f,g:I\rightarrow X$ ([[Continous Function#Path]]), a *homotopy of paths*, is a homotopy $f_t:I\rightarrow X$ with $f_0=f$, $f_1=g$ and $f_{t_1}(0)=f_{t_2}(0)$, $f_{t_1}(1)=f_{t_2}(1)$ for any $t_1,t_2\in I$. 
We also say $f_t$ is a *homotopy with fixed endpoints*. 
We say two paths are homotopic if they are homotopic by a homotopy of paths and write $f\simeq g$.