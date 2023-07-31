For an [[Affine Variety]] $V\subseteq \mathbb{A}^n_k$ over a [[Field]] $k$, with local ring at $p\in V$ $\mathcal{O}_{V,p} = \{ \frac{f}{g} \in k(V) | f,g\in k[V], g(p)\neq 0 \}$ and maximal ideal $m_{V,p} = \{\Phi \in \mathcal{O}_{V,p} | \Phi(p) = 0\}$, the *Zariski Tangent Space* of $V$ at $p$ is defined as 
$$ T_p(V) = Hom_{k}(m_{V,p}/m_{V,p}^2,k)$$
This is a [[Vector Space]] over $k$ of dimension $\leq n$.
If $I(V) = (f_1,\dots,f_s)$ and $d_p(f_i) = \frac{\partial f_i}{\partial x_i}(p) x_1 + \dots + \frac{\partial f_i}{\partial x_n}(p) x_n$, then $T_p(V)$ is the subspace of $k^n$ defined by $d_p(f_1) = \dots = d_p(f_s) = 0$.
If $dimT_p(V) = dim_pV$, $p$ is a smooth point, otherwise it is singular ([[Singularities]] )