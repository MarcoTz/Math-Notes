A polynomial ([[Polynomial Ring]]) $P(z)\in \mathbb{Q}[z]$ with $P(n)\in\mathbb{Z}$ for all $n\in\mathbb{Z}$ with $n>>0$ is called *numerical polynomial*.

For a numerical polynomial $P$, there are $c_0,c_1,\dots,c_r\in \mathbb{Z}$ s.t. 
$$ P(z) = c_0 {z \choose r} + c_1 {z \choose r-1} + \dots + c_r$$
where ${z \choose r}$ is the [[Binomial Coefficient]].
This means in particular, that $P(n)\in\mathbb{Z}$ for all $n\in \mathbb{Z}$.

If for any function $f:\mathbb{Z}\rightarrow \mathbb{Z}$ there is a numerical polynomial $Q(z)$ s.t. the difference function $\Delta f := f(n+1)-f(n) = Q(n)$ for $n>>0$, then there is a numerical polynomial $P$ with $f(n) = P(n)$ for all $n>>0$.