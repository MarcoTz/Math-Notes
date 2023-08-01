A *projective toric variety* is a [[Projective Variety]] $V$ containing a torus $T_N$ ([[Algebraic Torus]]) s.t. the action of $T_N$ on itself extends to an action of $T_N$ on $V$ s.t. the map $T_N \times V \rightarrow V$ given by the group action ([[Group Actions]]) is a morphism.

$\mathbb{P}^n$ ([[Projective Space]]) is a toric variety with torus 
$$T_{\mathbb{P}^n} = \mathbb{P}^n\setminus V(x_0\dots x_n) = \{(a_0:\dots:a_n) \in \mathbb{P}^n | a_0\dots a_n \neq 0\} = \{(1:t_1:\dots:t_n) | t_1,\dots,t_n\in\mathbb{C}^*\} \cong (\mathbb{C}^*)^n$$ 
Given a finite set $\mathcal{A} \subseteq M$, let $\Phi_{\mathcal{A}} : T_N \rightarrow \mathcal{C}^s$ $t\mapsto (\chi^{m_1}(t),\dots,\chi^{m_s}(t))$ and $\pi : (\mathcal{C}^*)^s \rightarrow T_{\mathbb{P}^{s-1}}$. Then the toric variety $X_{\mathcal{A}}$ is the Zariski-closure ([[Zariski Topology]]) of $\text{im}(\pi\circ \Phi_{\mathcal{A}})$ in $\mathbb{P}^{s-1}$.
$\dim X_{\mathcal{A}}$ is equal to the dimension of the smallest affine subspace of $M_{\mathbb{R}}$ containing $\mathcal{A}$ (compare [[Affine Toric Variety]]).
$\mathbb{Z}\mathcal{A}$ is the character lattice of $X_{\mathcal{A}}$ ([[Character group of the torus]]).
If $P = Conv(\mathcal{A})$ is the [[Polytope]] defined by $\mathcal{A}$, then we have $dim X_{\mathcal{A}} = dimP$ 

A projective toric variety $X_{\mathcal{A}}\subseteq \mathbb{P}^{s-1}$ has an *affine cone* $\hat{X}_{\mathcal{A}}\subseteq \mathbb{C}^s$.
Given the affine toric variety $Y_{\mathcal{A}}$ defined by $\mathcal{A}$ as well with toric ideal ([[Lattice Ideal]]) $I_L = \langle x^{\alpha} - x^{\beta} | \alpha,\beta \in \mathbb{N}^s, \alpha-\beta\in L\rangle$, the following are equivalent 
* $Y_{\mathcal{A}} \subseteq \mathbb{C}^s$ is the affine cone $\hat{X}_{\mathcal{A}}$ of $X_{\mathcal{A}}\subseteq \mathbb{P}^{s-1}$ 
* $I_L = I(X_{\mathcal{A}})$ 
* $I_L$ is homogeneous 
* There is some $u\in N$ and $k>0$ in $\mathbb{N}$ s.t. $\langle m_i,u\rangle = k$ for $i=1,\dots,s$ 

If $P\subseteq M_{\mathbb{R}}$ is a full-dimensional very ample ([[Very Ample Polytope]]) lattice polytope we have 
* for any vertex $m_i\in P\cap M$, the affine piece ([[Affine Pieces of a Projective Toric Variety]]) $X_{P\cap M} \cap U_i$ is equal to $U_{\sigma_i} = Spec(\mathbb{C}[\sigma_i^{\vee} \cap M])$ where $\sigma_i\subseteq N_{\mathbb{R}}$ is the strongly convex rational polyhedral cone ([[Strongly convex cone]],[[Rational Polyhedral Cone]]) dual to $Cone(P\cap M - m_i)$ and $\dim \sigma_i = n$ 
* The torus of $X_{P\cap M}$ has character lattice $M$ and thus is the torus $T_N$