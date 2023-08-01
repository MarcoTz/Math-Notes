Let $X_{\Sigma}$ be a [[Toric Variety]] corresponding to a [[Fan]] $\Sigma$. Then each $\sigma\in\Sigma$ has a distinguished point $\gamma_{\sigma} \in U_{\sigma} \subseteq X_{\Sigma}$ ([[Distinguished Point of an affine toric variety]]).
Then the *torus orbit* is defined as 
$$ O(\sigma) = T_N\gamma_{\sigma} \subseteq X_{\Sigma}$$ 

If $\sigma$ is a strongly convex rational polyhedral cone ([[Strongly convex cone]], [[Rational Polyhedral Cone]]) in $N_{\mathbb{R}}$, $N_{\sigma}$ is the sublattice ([[Lattice]]) spanned by the points $\sigma \cap N$ and $N(\sigma) = N/N_{\sigma}$ then 
* There is a perfect pairing ([[Pairing]]) $\langle\cdot,\cdot\rangle : \sigma^{\bot} \cap M \times N(\sigma) \rightarrow \mathbb{Z}$ induced by the pairing on $M\times N$.
* This perfect pairing induces a natural isomorphism $Hom_{\mathbb{Z}}(\sigma^{\bot} \cap M,\mathbb{C}^*) \cong T_{N(\sigma)}$ 

For some $\tau \in \Sigma$ we write $V(\tau) = \overline{O(\tau)}$ , then $V(\tau) = \bigcup_{\tau\preccurlyeq \sigma} O(\sigma)$ and if we write $\overline{\sigma}$ for the image of $\sigma$ under the quotient map $N_{\mathbb{R}}\rightarrow N(\tau)_{\mathbb{R}}$ (see [[Orbit-Cone Correspondence]]), let $Star(\tau) = \{\overline{\sigma} \subseteq N(\tau)_{\mathbb{R}} | \tau \preccurlyeq \sigma \in \Sigma\}$, which is also a fan and $V(\tau) \cong X_{Star(\tau)}$ 