For a [[Topological Space]] $X$, the *$n$-th homotopy group* $\pi_n(X,x_0)$ at $x_0\in X$ is defined to be the set of [[Continous Function]]s $\varphi : I^n \rightarrow X$ with $\varphi(\partial I^n) = \{x_0\}$ modulo [[Homotopy]] with $\varphi + \psi(t_1,\dots,t_n) = \varphi(2t_1,t_2,\dots,t_n)$ for $t_1 \in [0,\frac{1}{2}]$ and $\varphi+\psi(t_1,\dots,t_n) = \psi(2t_1-1,t_2,\dots,t_n)$ for $t_1\in [\frac{1}{2},1]$. 

$\pi_1(X,x_0)$ is [[The Fundamental Group]] of $X$ at $x_0$.
For $n\geq 2$, $\pi_n(X,x_0)$ is an [[Abelian Group]].
If $X$ is path-connected ([[Path Connectedness]]), $\pi_n(X,x_0) \cong \pi_n(X,y_0)$ for any $x_0,y_0\in X$.

Let $\gamma,f,g : (I^n,\partial I^n) \rightarrow (X,x_0)$ be continuous maps, then wa have 
* $\gamma(f+g) \simeq \gamma f + \gamma g$
* $(\gamma g)f \simeq \gamma (gf)$
* $1f \simeq f$

Let $p:(\tilde{X},\tilde{x_0}) \rightarrow (X,x_0)$ is a covering space ([[Covering Spaces]]). Then $p$ induces isomorphisms $p_*:\pi_n(\tilde{X},\tilde{x_0}) \rightarrow \pi_n(X,x_0)$ for all $n\geq 2$.

If $X_{\alpha}$ is a collection of path-connected spaces, then there are isomorphisms $\pi_n(\Pi_{\alpha}X_{\alpha}) \cong \Pi_{\alpha}\pi_n(X_{\alpha})$ for all $n$.

### Homotopy groups of $S^n$

The following table shows $\pi_i(S^n)$

| $n$/$i$ | $1$ | $2$ | $3$ | $4$ | $5$ | $6$ | $7$ | $8$ | $9$ | $10$ | $11$ | $12$ |
|-----|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | $\mathbb{Z}$ | $0$ | $0$ | $0$ | $0$ | $0$ | $0$| $0$ | $0$ | $0$ | $0$ | $0$ | 
| $2$ | $0$| $\mathbb{Z}$| $\mathbb{Z}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_{12}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_3$ | $\mathbb{Z}_{15}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2 \times \mathbb{Z}_2$ | 
| $3$ | $0$ | $0$| $\mathbb{Z}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_{12}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_3$ | $\mathbb{Z}_{15}$ | $\mathbb{Z}_2$| $\mathbb{Z}_2\times \mathbb{Z}_2$|
| $4$| $0$ | $0$| $0$| $\mathbb{Z}$| $\mathbb{Z}_2$| $\mathbb{Z}_2$| $\mathbb{Z}\times \mathbb{Z}_{12}$| $\mathbb{Z}_2\times\mathbb{Z}_2$ | $\mathbb{Z}_2\times\mathbb{Z}_2$ | $\mathbb{Z}_{24} \times \mathbb{Z}_3$ | $\mathbb{Z}_{15}$ | $\mathbb{Z}_2$|
| $5$ | $0$ | $0$ | $0$| $0$| $\mathbb{Z}$| $\mathbb{Z}_2$| $\mathbb{Z}_2$ | $\mathbb{Z}_{24}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_{30}$| 
| $6$ | $0$ | $0$| $0$ | $0$ | $0$ | $\mathbb{Z}$| $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_{24}$ | $0$ | $\mathbb{Z}$ | $\mathbb{Z}_2$|
|$7$| $0$ | $0$| $0$| $0$| $0$| $0$|$\mathbb{Z}$| $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_{24}$| $0$ | $0$|
|$8$| $0$ | $0$| $0$| $0$| $0$| $0$| $0$| $\mathbb{Z}$ | $\mathbb{Z}_2$ | $\mathbb{Z}_2$ | $\mathbb{Z}_{24}$ |$0$|




