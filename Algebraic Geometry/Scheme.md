An *affine scheme* is a locally ringed space $(X,\mathcal{O}_X)$ which is isomorphic as a locally [[Ringed Space]] to the [[Spectrum]] of some ring. 

A *scheme* is a locally ringed space $(X,\mathcal{O}_X)$ s.t. every point of $X$ has a neighborhood $U$ s.t. $(U,\mathcal{O}_X|_U)$ is an affine scheme.

We call $X$, the *underlying space* of the scheme, often denoted $sp(X)$ when we use $X$ to mean the scheme $(X,\mathcal{O}_X)$, and $\mathcal{O}_X$ is called the *structure [[Sheaf]]* of $X$.

A morhpism of schemes is a morphism of locally ringed spaces and an isomorphism of schemes is a morphism with two-sided inverse.

The *dimension* of a scheme $X$ is the dimension of $sp(X)$, as defined for varieties ([[Affine Variety#Dimension]]).
The *codimension* of an irreducible ([[Irreducible Sets]]) subset $Z$ of $X$, denoted $codim(Z,X)$ is the supremum of integers, s.t. there is a chain $Z=Z_0 \subseteq Z_1\dots \subseteq Z_n$ of distinct closed irreducible subsets of $X$. For any closed subset $Y$ of $X$, we define 
$codim(Y,X)=inf_{Z\subseteq Y, \text{ irreducible}} codim(Z,X)$ 