Let $X$ be a curve ([[Curve (Scheme)]]) over a [[Field]] $k$.
Then the *Jacobian variety* of $X$ is a [[Scheme]] $J$ of finite type over $k$ ([[Finite Morphisms of Schemes]],[[Scheme over a Scheme]]) with an element $\mathcal{L} \in Pic^{\circ}(X/J)$ ([[Picard Group]]) s.t. the following holds:
for any scheme $T$ of finite type over $k$ and $\mathcal{M}\in Pic^{\circ}(X/T)$ there is a unique morphism $f:T\rightarrow J$ s.t. $f^*\mathcal{L} \cong \mathcal{M}$ in $Pic^{\circ}(X/T)$

If $J$ exists it is unique.
$J$ is always a [[Group Scheme]] over $k$ with $e:Spec k\rightarrow J$ defined by $0\in Pic^{\circ}(X/k)$, $\rho:J\rightarrow J$ defined by $\mathcal{L}^{-1}\in Pic^{\circ}(X/k)$, $\mu:J\times J \rightarrow J$ defined by $p_1^*\mathcal{L} \times p_2^*\mathcal{L} \in Pic^{\circ}(X/J\times J)$.

If $X$ is an elliptic curve ([[Genus of a Curve]]), $P_0\in X$, $J=X$ and $\mathcal{L} = \mathcal{L}(\Delta)\otimes p_1^*\mathcal{L}(-P_0)$ where $\Delta \subseteq X\times X$ is the diagonal.
Then $J,\mathcal{L}$ is a Jacobian Variety for $X$.
The resulting structure of group variety on $J$ induces the same group structure on $X,P_0$.
