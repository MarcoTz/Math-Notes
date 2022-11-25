Let $R$ be a commutative [[Ring]]. A *multiplicatively closed* subset $S\subseteq R$ is a subset s.t. $1\in S$ and for any $x,y\in S$ we have $xy\in S$.

Then we define an equivalence relation ([[Relation#Equivalence Relations]]) on $R\times S$, where $(a,s)\sim (b,t)$ iff $u(at-bs)=0$ for some $u\in S$.
We write $\frac{a}{s}$ for the equivalance class of $(a,s)$.
On the set of equivalence classes, written $S^{-1}R$, we can define multiplication and addition the following way

* $\frac{a}{s} + \frac{b}{t} = \frac{at+bs}{st}$
* $\frac{a}{s}*\frac{b}{s} = \frac{ab}{st}$

With this, $S^{-1}R$ is a ring, called the *localization of $R$ at $S$.

If $S = R\setminus p$ for some prime ideal $p$ we write $R_p$ for $S^{-1}R$. In this case, $R_P$ is a local ring.
If $S=R\setminus\{0\}$, then $S^{-1}R$ is the [[Quotient Field]] of $R$.

