Let $N,N^{\prime}$ be two [[Lattice]]s with a $\mathbb{Z}$-linear mapping $\bar{\Phi}:N\rightarrow N^{\prime}$, and $\Sigma,\Sigma^{\prime}$ be [[Fan]]s in $N_{\mathbb{R}}$ and $N^{\prime}_{\mathbb{R}}$ compatible with $\bar{\Phi}$ ([[Fan-Compatible Map]]).
Then we have the corresponding toric morphism $\Phi : X_{\Sigma} \rightarrow X_{\Sigma^{\prime}}$ ([[Toric Morphism 1]]) and with $N_0 = ker(\bar{\Phi})$ an [[Exact Sequence]]
$$ 0 \rightarrow N_0 \rightarrow N \xrightarrow{\bar{\Phi}} N^{\prime} \rightarrow 0$$
Then $\Sigma_0 = \{\sigma \in \Sigma | \sigma \subseteq (N_0)_{\mathbb{R}}\}$ is a subfan of $\Sigma$.

We say $\Sigma$ is *split by* $\Sigma^{\prime}$ and $\Sigma_0$ if there is a subfan $\hat{\Sigma}\subseteq \Sigma$ s.t. 
* $\bar{\Phi}$ maps each cone $\hat{\sigma}\in\hat{\Sigma}$ bijectively to a cone $\sigma^{\prime}\in\Sigma^{\prime}$ s.t. $\bar{\Phi}(\hat{\sigma}\cap N) = \sigma^{\prime} \cap N^{\prime}$ and the map $\hat{\sigma}\rightarrow \sigma^{\prime}$ is a biejction $\hat{\Sigma} \xrightarrow{\sim} \Sigma^{\prime}$ 
* Given cones $\hat{\sigma}\in\hat{\Sigma}$ and $\sigma_0 \in \Sigma_0$, the sum $\hat{\sigma} + \sigma_0$ lies in $\Sigma$ and every cone of $\Sigma$ has this form

If $\Sigma$ is split by $\Sigma^{\prime}$ and $\Sigma_0$ then $X_{\Sigma}$ is a locally trivial fiber bundle ([[Fiber Bundle]]) over $X_{\Sigma^{\prime}}$, i.e. $X_{\Sigma^{\prime}}$ has a cover by affine open subsets $U$ s.t. $\Phi^{-1}(U) \cong X_{\Sigma_0,N_0} \times U$ 