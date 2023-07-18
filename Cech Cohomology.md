
For a [[Topological Space]] $X$, $\mathcal{U} = \{U_i\}_{i\in I}$ open covering of $X$ s.t. $I$ is well-ordered ([[Order]])
For $i_0,\dots,i_p \in I$, the interection $U_{i_0} \cap \dots \cap U_{i_p}$ is denoted by $U_{i_0,\dots,i_p}$.
$\mathcal{F}$ sheaf ([[Sheaf]]) of abelian groups ([[Abelian Group]]) on $X$, then $C^{\cdot}(\mathcal{U},\mathcal{F})$ is the [[Complex]] defined as follows:

For $p\geq 0$, $C^p(\mathcal{U},\mathcal{F}) = \Pi_{i_0<\dots<i_p} \mathcal{F}(U_{i_0,\dots,i_p}$), and the coboundary map $d:C^p\rightarrow C^{p+1}$ is defined as $(d\alpha)_{i_0,\dots,i_{p+1}} = \sum_{k=0}^{p+1} (-1)^k \alpha_{i_0,\dots,\hat{i_k},\dots, i_{p+1}} \mid_{U_{i_0,\dots,i_{p+1}}}$   ($\hat{i}$ means ommitting $i$).

Then the *$p$-th Cech cohomology group of $\mathcal{F}$ wrt $\mathcal{U}$* is defined as $\check{H}^p(\mathcal{U},\mathcal{F}) = h^p(C^{\cdot}(\mathcal{U},\mathcal{F})$ ([[cohomology]]). 

We have $\check{H}^0(\mathcal{U},\mathcal{F}) \cong \Gamma(X,\mathcal{F})$. 
If $\mathcal{F}$ is a [[Flasque Sheaf]], all $\check{H}^p(\mathcal{U},\mathcal{F}) = 0$.
If $X$ is a [[Noetherian Scheme]] and separated ([[Separated Morphisms]]), $\mathcal{U}$ is an affine cover ([[Spectrum]]) and $\mathcal{F}$ a quasi-coherent sheaf on $X$ ([[Coherent Sheaf of modules]]), then $\check{H}^p(\mathcal{U},\mathcal{F}) \xrightarrow{\sim} H^p(X,\mathcal{F})$ ([[Cohomology Functor]]).