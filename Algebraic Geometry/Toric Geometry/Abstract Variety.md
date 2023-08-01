Let $\{V_{\alpha}\}_{\alpha}$ be a finite collection of affine varieties ([[Affine Variety]]) s.t. for all pairs $\alpha,\beta$ we have Zariski-open sets $V_{\beta\alpha} \subseteq V_{\alpha}$ and isomorphisms $g_{\beta\alpha} : V_{\beta\alpha} \cong V_{\alpha\beta}$ satisfying
* $g_{\alpha\beta} = g_{\beta\alpha}^{-1}$ for all $\alpha, \beta$
* $g_{\beta\alpha}(V_{\beta\alpha} \cap V_{\gamma\alpha}) = V_{\alpha\beta} \cap V_{\gamma\beta}$ and $g_{\gamma\alpha} = g_{\gamma\beta} \circ g_{\beta\alpha}$ on $V_{\beta\alpha} \cap V_{\gamma\alpha}$ for all $\alpha,\beta,\gamma$.
Then let $Y = \bigsqcup_{\alpha} V_{\alpha}$ ([[Disjoint Union]]) and define a relation $\sim$ on $Y$ where $a\sim b$ iff $a\in V_{\alpha}$, $b\in V_{\beta}$ for some $\alpha$. $\beta$ with $b = g_{\beta\alpha}(a)$.
$\sim$ is an equivalence relation on $Y$ and the quotient space $X = Y/\sim$ is called an *abstract variety* defined by the $V_{\alpha}$ and $g_{\beta\alpha}$.

If $X$ and $Y$ are abstract varieties with affine open covers $X=\bigcup_{\alpha} U_{\alpha}$ and $Y = \bigcup_{\beta} U_{\beta}^{\prime}$, a morphism $\Phi : X \rightarrow Y$ is a Zariski continuous map s.t. $\Phi |_{U_{\alpha}\cap\Phi^{-1}(U^{\prime}_{\beta})}: U_{\alpha} \cap \Phi^{-1}(U_{\beta}^{\prime}) \rightarrow U_{\beta}^{\prime}$ is a morphism.

If $U$ is an open subset of an abstract variety $X$ and $W_{\alpha} = g_{\alpha}^{-1}(U\cap U_{\alpha}) \subseteq V_{\alpha}$, then a function $\Phi:U\rightarrow k$ is *regular* if $\Phi\circ g_{\alpha}|_{W_{\alpha}}$ is regular for all $\alpha$.
Then the structure sheaf $\mathcal{O}_X$ of $X$ ([[Ringed Space]]) is defined as $\mathcal{O}_X(U) = \{ \Phi : U \rightarrow k | \Phi \text{ regular}\}$.

Any closed subset $Y\subseteq X$ of an abstract variety is also an abstract variety with ideal sheaf ([[Sheaf of Ideals]]) $\mathcal{I}_Y(U) = \{f \in \mathcal{O}_X(U) | f(p) = 0 \forall p\in Y\cap U\}$ 