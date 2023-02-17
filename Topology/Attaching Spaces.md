Given two [[Topological Space]]s $X$ and $Y$ with a subspace $A\subseteq Y$ and a [[Continous Function]] $f:A\rightarrow X$, we form the quotient space ([[Topology/Quotient Space]]) of the [[Disjoint Union]] $X\sqcup Y$ under the identifications $a\sim f(a)\forall a\in A$.
We denote this space by $X\sqcup_f Y$ and say $Y$ is *attached* to $X$ along $A$ via $f$.


### Mapping Cylinder 

Given a Continous Function $f:X\rightarrow Y$, the *mapping cylinder* of $f$ is the quotient space  of $X\times I\sqcup Y$  where $I=[0,1]$ under the equivalence relation ([[Relation#Equivalence Relations]]) identifying $(x,1)\in X\times I$ with $f(x)\in Y$.

Intuitively, the mapping cylinder is a space containing both $X$ and $Y$, connecting each $x\in X$ to $f(x)\in Y$ with a line segment.

This is the space obtained from $Y$ by attaching $X\times I$ along $X\times \{1\}$

### Mapping Cone

Similarly to the mapping cylinder, the *mapping cone* of a map $f:X\rightarrow Y$ is the space $C_f = Y\sqcup_f CX$ ([[Cone]]), so $CX$ is attached to $Y$ along $X\times \{1\}$ via $(x,1)\sim f(x)$.
We can also view $C_f$ as the mapping cylinder $M_f/X$ where we identify $X$ with  $X\times \{0\}$

### Homotopies and Attaching maps

If $(X_1,A)$ is a CW pair ([[Cell Complexes]]) and the attaching maps $f,g:A\rightarrow X_0$ rae homotopic ([[Homotopy]]), then $X_0\sqcup_f X_1 \simeq X_0\sqcup_g X_1$