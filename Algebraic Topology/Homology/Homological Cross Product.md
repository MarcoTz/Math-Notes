
Let $X$ and $Y$ be [[Topological Space]]s with singular chain complexes ([[Singular Homology]]) $C_n(X;R)$ and $C_n(Y;R)$. 
Then the *cross product* is defined the following way

$$\times : C_m(X;R)\otimes C_n(Y;R) \xrightarrow{\times} C_{m+n}(X\times Y;R)$$
$$ f\times g = \sum_{\sigma} (-1)^{|\sigma|}(f\times g) l_{\sigma}$$
where $\sigma$, $|\sigma|$ and $l_{\sigma}$ are defined the following way. For $f:\Delta^m\rightarrow X$ and $g:\Delta^n \rightarrow Y$ singular simplices, let $v_0,\dots,v_m$ be the vertices of $\Delta^m$ and $w_0,\dots,w_n$ the vertices of $\Delta^n$ ([[Simplices]]) and consider the pairs of indices $(i,j)$ with $0\leq i\leq m$, $0\leq j\leq n$ as a grid in $\mathbb{R}^2$. Then $\sigma$ is any path from $(0,0)$ to $(m,n)$ along these points $(i,j)$ always going either upwards or right. 
For such a $\sigma$, $|\sigma|$ is the number of squares laying below this path, and $l_{\sigma}:\Delta^{m+n}\\rightarrow \Delta^m\times \Delta^n$ is the [[Linear Map]] seinding the vertex $k$ of $\Delta^{m+n}$ to $(v_{i_k},w_{j_k})$ where $(i_k,j_k)$ is the $k$th vertex of $\sigma$.

Then we have $\partial (f\times g) = \partial f \times g + (-1)^m f\times \partial g$, so this cross product extends to homology and gives a map 

$$ \times : H_m(X;R)\otimes H_n(Y;R)\rightarrow H_{n+m}(X\times Y;R)$$ 
