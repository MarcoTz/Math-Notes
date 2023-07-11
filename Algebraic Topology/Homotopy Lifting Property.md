A map $p:E\rightarrow B$ between [[Topological Space]]s has the *homotopy lifting property* wrt a space $X$ if for any [[Homotopy]] $g_t : X \rightarrow B$ and a map $\tilde{g}_0 : X\rightarrow E$ lifting $g_0$ (i.e. $p\tilde{g}_0 = g_0$) there is a homotopy $\tilde{g}_t : X \rightarrow E$ lifting $g_t$.

If $p:E\rightarrow B$ has the homotopy lifting property wrt. disks $D^k$ for all $k\geq 0$, let $b_0\in B$, $x_0\in F = p^{-1}(b_0)$.
Then the map $p_* : \pi_n(E,F,x_0) \rightarrow \pi_n(B,b_0)$ ([[Homotopy Groups]]) is an isomorphism for all $n\geq 1$.
If $B$ is path-connected ([[Path Connectedness]]) there is then a long exact sequence 
$$ \dots \rightarrow \pi_n(F,x_0) \rightarrow \pi_n(E,x_0) \xrightarrow{p_*} \pi_n(B,b_0) \rightarrow \pi_{n-1}(F,x_0) \rightarrow \dots \rightarrow \pi_0(E,x_0) \rightarrow 0$$ 
