Cohomology groups $H^n$ are the [[Homology]] groups of a cochain complex ([[Chain Complexes#Cochain Complex]]), $H^n = Ker\delta/Im\delta$.
Many of the results in homology also apply to cohomology.

Any chain map ([[Chain Complexes#Chain maps]]) between chain complexes of free abelian groups ([[Free Groups]]) that induces isomorphisms on homology groups also induces isomorphisms on cohomology groups with any coefficient group $G$.

### Singular Cohomology 

The cohomology groups of singular homology are given by the *singular n-cochains with coefficients in G*, $C^n(X;G)=Hom(C_n(X),G)$.
The *coboundary map* $\delta:C^n(X;G)\rightarrow C^{n-1}(X;G)$ is the dual of the regular boundary map $\partial$, mapping $\varphi\in C^n(X;G)$ to the composition $\partial \circ \varphi$. This gives the following formula for a $(n+1)$-simplex $\sigma:\Delta^{n+1}\rightarrow X$

$$ \delta \varphi(\sigma) = \sum_i (-1)^n \varphi(\sigma_{|[v_0,\dots,\hat{v_i},\dots,v_{n+1}]})$$
Elements in $Ker\delta$ are called *cocycles* and elements in $Im\delta$ *coboundaries* and we have $\delta\varphi = \varphi\delta$

### Reduced Cohomology Groups

Reduced cohomology groups are the cohomology groups of the dual complex of the augmented chain complex $\dots C_0(X)\xrightarrow{\varepsilon}\mathbb{Z}\rightarrow 0$ 
We also have $\tilde{H}^n(X;G)=H^n(X;G)$ for $n>0$ and by the [[Universal Coefficient Theorem]] $\tilde{H}^0(X;G)=Hom(\tilde{H}_0(X),G)$ 

### Relative Cohomology Groups

Dualizing the short exact sequence of a pair $(X,A)$ we get the short exact sequence 
$$ 0 \leftarrow C^n(A;G) \xleftarrow{i^*} C^n(X;G) \xleftarrow{j^*} C^n(X,A;G) \leftarrow 0 $$ with inclusion $i$ and quotient map $j$. This gives the long exact sequence of cohomology groups

$$ \dots H^n(X,A;G) \xrightarrow{j^*} H^n(X;G) \xrightarrow{i^*} H^n(A;G) \xrightarrow{\delta} H^{n+1}(X,A;G) \rightarrow \dots $$ 
### Induced Homomorhpisms

The duals of induced chain maps $f_{\#}$ by $f:X\rightarrow Y$ are the induced cochain maps $f^{\#}$ which induce homomorhpisms $f^*:H^n(Y;G)\rightarrow H^n(X;G)$ with the relation $\delta f^{\#} = f^{\#}\delta$.
We have $(fg)^*=g^*f^*$ and $\mathbb{1}^*=\mathbb{1}$ 

If $f\simeq g:(X,A)\rightarrow (Y,B)$ then $f^*=g^*:H^n(Y,B)\rightarrow H^n(X,A)$  

### Excision

Let $X$ be a space with subspaces $Z\subseteq A\subseteq X$ s.t. $clZ\subseteq intA$. Then the inclusion $i:(X\setminus Z,A\setminus Z)\xhookrightarrow{} (X,A)$ induces isomorphisms $i^*:H^n(X,A;G)\rightarrow H^n(X\setminus Z,A\setminus Z)$

### Simplicial Cohomology 

The simplicial chain groups $\Delta_n(X,A)$ of  [[Delta-Complex]] $X$ with subcomplex $A$ dualize to cochain groups $\Delta^n(X,A)$ which then define the simplicial cohomology groups $H^n_{\Delta}(X,A;G)$. 
The dual maps of the inclusions $\Delta_n(X,A)\subseteq C_n(X,A)$ induce isomorphisms $H^n(X,A;G)\cong H^n_{\Delta}(X,A;G)$ 

### Cellular Cohomology

The following sequence defines a cochain comples, and its cohomology groups are the *cellular cohomology groups*,

$$ \dots \rightarrow H^{n-1}(X^{n-1},X^{n-2}) \xrightarrow{d_{n-1}} H^n(X^n,X^{n-1}) \xrightarrow{d_n} H^{n+1}(X^{n+1},X^n)\rightarrow \dots$$

We have $H^n(X;G) \cong Ketd_n/Imd_{n-1}$ and this cochain complex is isomorphic to the simplicial complex after applying $Hom(-,G)$.

### Mayer-Vietoris Sequences

In the absolute case we have the sequence 

$$ \dots H^n(X;G) \xrightarrow{\psi} H^n(A;G) H^n(A;G)\oplus H^n(B;G) \xrightarrow{\Phi} H^n(A\cap B;G)\rightarrow H^{n+1}(X;G)\rightarrow \dots $$ 
And in the relative case we have 

$$ \dots H^n(X,Y;G) \rightarrow H^n(A,C;G) \oplus H^n(B,D;G) \rightarrow H^n(A\cap B,C\cap D; G) \rightarrow \dots $$ 

