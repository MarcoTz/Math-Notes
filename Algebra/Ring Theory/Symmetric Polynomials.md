Given a [[Factorial Ring]] $R$ with [[Polynomial Ring]] $R[X_1,\dots,X_n]$, a polynomial $f\in R[X_1,\dots,X_n]$ is called *symmetric* , if 

$f(X_1,\dots,X_n) = f(X_{\pi(1)}, \dots, X_{\pi(n)}) \quad \forall \pi \in S(n)$

([[Symmetric Group]])

For any two symmetric polynomials $f,g$ and $r,s\in R$, $fg$ and $rf+sg$ are also symmetric.

#### Elementary Symmetric Polynomials

In $R[X_1,\dots,X_n]$ the *elementary symmetric polynomials* are the polynomials $s_0,\dots, s_n$ defined by 

$s_0 = 1$ 
$s_1 = X_1 + \dots + X_n = \sum_{i=1}^n X_n$
$s_2 = X_1X_2 + \dots + X_1X_n + X_2X_3 + \dots + X_{n-1}X_n = \sum_{1\leq i<j\leq n} X_iX_j$
$\vdots$ 
$s_k = \sum_{1\leq i_1< i_2< \dots < i_k \leq n} X_{i_1}\dots X_{ik}$
$\vdots$
$s_n = X_1\dots X_n$ 


For any polynomial $g\in R[Y_1,\dots,Y_n]$, the polynomial $f(X_1,\dots,X_n) = g(s_1,\dots,s_n)$ is a symmetric polynomial.
Conversely, for any symmetric polynomial $f(X_1,\dots,X_n)$, there is a polynomial $g\in R[Y_1,\dots,Y_n]$ with $f(X_1,\dots,X_n) = g(s_1,\dots,s_n)$.