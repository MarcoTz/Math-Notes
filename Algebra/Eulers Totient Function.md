For any $n\in \mathbb{N}$, the function $\varphi(n) = |\{k\in\mathbb{N} | k<n , gcd(k,n)=1\}|$ is called the *euler totient function*.
It has the following properties

1. If $m,n\in\mathbb{N}$ have $gcd(m,n)=1$ then $\varphi(nm) = \varphi(n)\varphi(m)$
2. if $p$ is prime and $k\in \mathbb{N}$, then $\varphi(p^k) = p^k-p^{k-1}$ 
3.  If $n = p_1^{k_1}\dots p_k^{k_s}$ with $k_1,\dots,k_s > 0$ and $p_1,\dots,p_s$ different prime numbers, then $\varphi(n) = (p_1^{k_1} - p_1^{k_1-1})\dots (p_s^{k_s}-p_s^{k_s-1}) = n(1-\frac{1}{p_1})\dots (1-\frac{1}{p_s})$
4. For any $n\in \mathbb{N}$ we have $n = \sum_{d|n} \varphi(d)$