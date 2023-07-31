An *affine toric variety* is an irreducible ([[Irreducible Sets]]) [[Affine Variety]] $V$ containing a torus $T_N \cong (\mathbb{C}^*)^n$ ([[Algebraic Torus]]) as an open subset s.t. the group action of $T_N$ on itself ([[Group Actions]]) extends to an action of $T_N$ on $V$ s.t. the map $T_N \times V \rightarrow V$ given by the group action is a morphism.

For a [[Lattice]] $M$ and $\mathcal{A} = \{m_1,\dots,m_s\}\subseteq M$ a finite subset, we have a map $\Phi_{\mathcal{A}} : T_n \rightarrow \mathbb{C}^s$ $t\mapsto (\chi^{m_1}(t),\dots,\chi^{m_s}(t))$.
Then the Zariski-closure of $\Phi_{\mathcal{A}}(T_N)$ is an affine toric variety denoted by $Y_{\mathcal{A}}$. 
The character group of $Y_{\mathcal{A}}$ is given by $\mathbb{Z}\mathcal{A}$ and $dimY_{\mathcal{A}}=rank\mathbb{Z}\mathcal{A}$.
The ideal of $Y_{\mathcal{A}}$ is given by 
$$ I(Y_{\mathcal{A}}) = \langle x^{l_+} - x^{l_-} | l \in L\rangle$$
where $L$ is the kernel of the map $\hat{\Phi}_{\mathcal{A}}:\mathbb{Z}^s \rightarrow M$ induced by $\Phi_{\mathcal{A}}$ sending $e_1,\dots,e_n$ to $m_1,\dots,m_s$ and for $l = (l_1,\dots,l_s)\in L$ $l_+ = \sum_{l_i>0} l_ie_i$ and $l_- = -\sum_{l_i<0} l_ie_i$.

If $V$ is an affine variety, then the following are equivalent 
* $V$ is an affine toric variety
* $V = Y_{\mathcal{A}}$ for some finite set $\mathcal{A}$ in a lattice
* $V$ is an affine variety defined by a toric ideal ([[Lattice Ideal]])
* $V = Spec(\mathbb{C}[S])$ for an [[Affine Semigroup]] $S$

If $\sigma \subseteq N_{\mathbb{R}}$ is a [[Rational Polyhedral Cone]] with [[Semigroup]] $S_{\sigma} = \sigma^{\vee} \cap M$ ([[Dual Polyhedral Cone]]), then $U_{\sigma} = Spec(\mathbb{C}[S_{\sigma}]) = Spec(\mathbb{C}[\sigma^{\vee} \cap M])$ is an affine toric variety and we have 
$$ \dim U_{\sigma} \Leftrightarrow \text{ the torus of } U_{\sigma} \text{ is } T_N = N\otimes_{\mathbb{Z}} \mathbb{C}^* \Leftrightarrow \sigma \text{ is strongly convex}$$
([[Strongly convex cone]])

Let $V = Spec(\mathbb{C}[S])$ be the affine toric variety of the affine semigroup $S$. Then there is a bijective correspondence between 
* points $p\in V$ 
* [[Maximal Ideal]]s $m\subseteq \mathbb{C}[S]$ 
* semigroup homomorphisms $S\rightarrow\mathbb{C}$ 
