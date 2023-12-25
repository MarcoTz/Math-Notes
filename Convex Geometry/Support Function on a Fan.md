Let $\Sigma$ be a [[Fan]] in $N_{\mathbb{R}}$. Then a *support function* $\varphi:|\Sigma| \rightarrow \mathbb{R}$ is a function linear on each cone of $\Sigma$.

A support function $\varphi$ is called *integral with respect to the [[Lattice]] $N$* if $\varphi(|\Sigma| \cap N) \subseteq \mathbb{Z}$. The set of all such support functions is denoted by $SF(\Sigma,N)$ 

If $D = \sum_{\rho} a_{\rho} D_{\rho}$ with Cartier data $\{m_{\sigma}\}$ ([[Cartier Divisors on Toric Varieties]]), the function $\varphi_D : |\Sigma| \rightarrow \mathbb{R}$ $u\mapsto \langle m_{\sigma},u\rangle$ if $u\in\sigma$ is a well-defined support function integral wrt $N$.
$\varphi_D(u_{\rho}) = -a_{\rho}$ for all $\rho\in\Sigma(1)$ s.t. $D = \sum_{\rho} \varphi_D(u_{\rho})D_{\rho}$.
The map $D\mapsto \varphi_D$ induces an isomorphism $CDiv_{T_N}(X_{\Sigma})\cong SF(\Sigma,N)$ 