Let $\sigma$ be a [[Convex Polyhedral Cone]]. Then a *face* of $\sigma$ is $\tau = H_m \cap \sigma$ for $m\in \sigma^{\vee}$ ([[Dual Polyhedral Cone]]), written $\tau \preccurlyeq \sigma$. If $\tau \neq \sigma$ we say $\tau$ is a *proper* face of $\sigma$, written $\tau \prec \sigma$ .
If $\dim \tau = \dim\sigma -1$, then $\tau$ is called a *facet* of $\sigma$.
A face of dimension $2$ is called an *edge*, and a face of dimension $1$ is called a *vertex*.

We have 
* Every face of $\sigma$ is a polyhedral cone 
* for two faces $\tau_1$ and $\tau_2$, $\tau_1\cap \tau_2$ is also a face
* if $\tau \preccurlyeq \sigma$ and $\tau^{\prime} \preccurlyeq \tau$, then $\tau^{\prime}\preccurlyeq \sigma$ 
* If $\tau\preccurlyeq \sigma$, $v,w\in\sigma$ and $v+w\in \tau$, then $v,w\in \tau$ 
* If $\sigma = H_{m_1}^+ \cap \dots \cap H_{m_s}^+$ for $m_i\in \sigma^{\vee}$ then $\sigma^{\vee} = Cone(m_1,\dots,m_s)$ 
* If $\dim\sigma = n$ then the facets of $\sigma$ are $\tau_i = H_{m_i} \cap \sigma$ 
* Every $\tau \prec \sigma$ is the intersection of two facets containing $\tau$.

For a face $\tau \preccurlyeq \sigma$ we let $\tau^{\bot} = \{m\in M_{\mathbb{R}} | \langle m,u\rangle = 0 \forall u\in \tau\}$ and $\tau^* = \{m\in \sigma^{\vee} | \langle m, u\rangle = 0 \forall u\in\tau\} = \sigma^{\vee} \cap \tau^{\bot}$.
$\tau^*$ is called the *dual face* of $\tau$.
We have 
* $\tau^*$ is a face of $\sigma^{\vee}$ 
* The map $\tau \mapsto \tau^*$ is a bijective inclusion-reversing correspondence between faces of $\sigma$ and $\sigma^{\vee}$ 
* $\dim\tau + \dim\tau^* = n$ 

If $\tau \preccurlyeq \sigma$ with $\tau = H_m\cap \sigma$ for $m\in\sigma^{vee} \cap M$, then we have $\mathbb{C}[S_{\tau}] = \mathbb{C}[S_{\sigma}]_{\chi^m}$ 