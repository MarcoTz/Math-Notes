The *Special Orthogonal Group* $SO(n)$ is the subgroup of $O(n)$ ([[Orthogonal Group]]) containing all orthogonal matrices with determinant $1$.

It is a path-connected [[Topological Space]] ([[Path Connectedness]], with the induced subspace topology) and even a [[Topological Group]]. It is also a CW complex ([[Cell Complexes]]).
To define the cell structure of $SO(n)$, let $r:\mathbb{R}^n\rightarrow O(n)$ map a vector $v$ to the reflection along the hyperplane orthogonal to $v$ and $\rho:\mathbb{R}^n\rightarrow SO(n)\quad v\mapsto r(v)r(e_1)$. Since $\rho$ is constant on lines in $\mathbb{R}^n$, we view it as a map $\mathbb{R}\mathbb{P}^{n-1}\rightarrow SO(n$)$ and then define $\rho : \mathbb{R}\mathbb{P}^I = \mathbb{R}\mathbb{P}^{i_1}\times \dots \mathbb{R}\mathbb{P}^{i_m}\rightarrow SO(n) \quad (v_1,\dots,v_m)\mapsto \rho(v_1)\dots\rho(v_m)$ where $I=(i_1,\dots,i_m)$ is a *admissable sequence*. $I$ is called admissable if $n>i_1>\dots>i_m>0$. Then the maps $\rho\varphi^I$ with $\varphi^I$ the characteristic maps of the cell structure of $\mathbb{R}\mathbb{P}^I$ ([[Projective Space]]) define a cell structure on $SO(n)$.

### [[Homology]] and [[Cohomology]]

$$ H^*(SO(n);\mathbb{Z}_2 \cong \bigotimes_{i \text{ odd}} \mathbb{Z}_2[\beta_i]/(\beta_i^{p_i})$$
where $|\beta_i| = i$ ([[Valuation Ring]]) and $p_i$ is the smallest power of $2$ with $|\beta_i^{p_i}|>n$
$$H_*(SO(n);\mathbb{Z}_2) = \Lambda_{\mathbb{Z}_2}[e^1,\dots,e^{n-1}]$$ where $H_*$ denotes the Pontryagin ring ([[Pontryagin Product]]) and $\Lambda$ the exterior algebra ([[Tensor Operations on Modules]])

$H_*(SO(n);\mathbb{Z})$ is a direct sum of copies of $\mathbb{Z}$ and $\mathbb{Z}_2$