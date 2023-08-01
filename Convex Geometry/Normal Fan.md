Let $P\subseteq M_{\mathbb{R}}$ be a full-dimensional [[Lattice]] [[Polytope]].
Then we can write $P$ as $P = \{m\in M_{\mathbb{R}} | \langle m,u_{F} \rangle \geq -a_F \forall F\}$ where $F$ denotes a facet of $P$.
For a face $Q$ of $P$ we write $\sigma_Q = Cone(u_F | f \text{ contains } Q)$.
Then the set $\Sigma_P = \{\sigma_Q | Q\preccurlyeq P\}$ is called the *normal fan* of $P$.
We have 
* for $\sigma_Q \in \Sigma_P$, each face of $\sigma_Q$ is in $\Sigma_P$ 
* for $\sigma_Q,\sigma_{Q^{\prime}}\in \Sigma_P$, the intersection $\sigma_Q \cap \sigma_{Q^{\prime}}$ is a face of both $\sigma_Q$ and $\sigma_{Q^{\prime}}$ 
* The normal fan of $P$ is a [[Fan]]
* $\dim Q + \dim \sigma_Q = n$ for all faces $Q\preccurlyeq P$ 
* $N_{\mathbb{R}} = \bigcup_{v \text{ vertex of } P} \sigma_v = \bigcup_{\sigma_Q \in \Sigma_P} \sigma_Q$ 
* for any $m\in M$ and $k\geq 1$, the polytopes $m+P$ and $kP$ have the same normal fan as $P$.

If $Q$ and $Q^{\prime}$ are two faces of $P$ then 
* $Q\subseteq Q^{\prime}$ iff $\sigma_{Q^{\prime}} \subseteq \sigma_Q$
* If $Q\subseteq Q^{\prime}$ then $\sigma_{Q^{\prime}}$ is a face of $\sigma_Q$ and all faces of $\sigma_Q$ are of this form
* $\sigma_Q \cap \sigma_{Q^{\prime}} = \sigma_{Q^{\prime\prime}}$ where $Q^{\prime\prime}$ is the smallest face of $P$ containing both $Q$ and $Q^{\prime}$ 