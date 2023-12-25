Let $X_{\Sigma}$ be a [[Toric Variety]] corresponding to a [[Fan]] $\Sigma$.
Then a [[Cartier Divisor]] $D$ on $X_{\Sigma}$ is also a [[Weil Divisor]] and we write $CDiv_{T_N}(X_{\Sigma})\subseteq Div_{T_N}(X_{\Sigma})$  for the group of $T_N$-invariant Cartier divisors ([[Toric-Invariant Divisors]]).

There is an [[Exact Sequence]]

$$ M \rightarrow CDiv_{T_N}(X_{\Sigma}) \rightarrow Pic(X_{\Sigma}) \rightarrow 0$$ ([[Picard Group]]) where the first map is $m\mapsto div(\chi^m)$ and the second is the quotient map.

Iff $\{u_{\rho} | \rho \in \Sigma(1)\}$ spans $N_{\mathbb{R}}$ there is a short exact sequence 
$$0 \rightarrow M \rightarrow CDiv_{T_N}(X_{\Sigma}) \rightarrow Pic(X_{\Sigma}) \rightarrow 0$$ 

For a strongly convex rational polyhedral cone $\sigma \subseteq N_{\mathbb{R}}$, every $T_N$-invariant Cartier divisor on $U_{\sigma}$ is the divisor of a character ([[Divisor of a Character]]) and $Pic(U_{\sigma}) = 0$.

If $\Sigma$ contains a cone of dimension $n$, $Pic(X_{\Sigma})$ is a free [[Abelian Group]] ([[Free Groups]])

Let $D=\sum_{\rho} a_{\rho}D_{\rho}$ be a divisor on $X_{\Sigma}$. Then the following are equivalent 
* $D$ is Cartier 
* $D$ is principal on $U_{\sigma}$ for all $\sigma \in \Sigma$ ([[Principal Divisor]])
* For each $\sigma \in \Sigma$ there is a $m_{\sigma} \in M$ s.t. $\langle m_{\sigma},u_{\rho}\rangle = -a_{\rho}$ for all $\rho \in \sigma(1)$ 
* For each $\sigma \in \Sigma_{max}$ there is some $m_{\sigma}$ with $\langle m_{\sigma}, u_{\rho}\rangle = -a_{\rho}$ for all $\rho \in \sigma(1)$ 
If these are all true then $m_{\sigma}$ is unique modulo $M(\sigma) = \sigma^{\bot} \cap M$ and if $\tau$ is a face of $\sigma$, then $m_{\sigma} = m_{\tau}$ mod $M(\tau)$. 
The set $\{m_{\sigma}\}_{\sigma\in\Sigma}$ is called *Cartier data* of $D$

There is a natural isomorphism $CDiv_{T_N}(X_{\Sigma}) \cong \ker(\bigoplus_i M/M(\sigma_i) \rightarrow \bigoplus_{i<j} M/M(\sigma_i\cap\sigma_j))$ 