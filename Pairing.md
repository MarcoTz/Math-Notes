Let $R$ be a commutative [[Ring]], $M$,$N$ $R$-[[Module]]s.
A *pairing* is a $R$-bilinear map $e:M\times N \rightarrow L$ s.t. 
* $e(r\cdot m, n) = e(m,r\cdot n) = r\cdot e(m,n)$ 
* $e(m_1+m_2,n) = e(m_1,n)+e(m_2,n)$
* $e(m,n_1+n_2) = e(m,n_1) + e(m,n_2)$

A pairing is called *perfect* if the map $m \mapsto e(m,\cdot)$ is an isomorphism of $R$-modules.

A pairing is non-degenerate on the right if $e(m,n) = 0$ implies $n=0$ and non-degenerate on the left if $e(m,n)=0$ implies $m=0$.
If if is both non-degenerate on the left and right, it is non-degenerate.

A pairing is called *alternating* if $N=M$ and $e(m,m) = 0$ for all $m$. 
In this case $e(m,n) = -e(n,m)$