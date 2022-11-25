For a ring $R$, the *polynomial ring* of $R$, denoted $R[x]$ is the ring with elements 

$f(x) = \sum_{i=0}^n a_ix^i$ with $a_i\in R$ and $x^0 = 1 \in R, n\in \mathbb{N}$

addition 

$\sum_{i=0}^n a_ix^i  + \sum_{j=0}^m b_j x^j = \sum_{i=0}^{max\{n,m\}} (a_i+b_i)x^i$ where $a_i = 0$ for $i>n$ and $b_i = 0$ for $i>m$

and multiplication 

$\sum_{i=0}^n a_ix^i \cdot \sum_{j=0}^m b_jx^j = \sum_{i=0}^n \sum_{j=0}^m a_ib_j x^{i+j}$

We then define the polynomial ring in multiple variables inductively as $R[x_1,\dots, x_n] = R[x_1,\dots,x_{n-1}][x_n]$.
A polynomial $f=a_0 + \dots + a_nx^n$ with $a_n = 1$ is called *normed*.
Polynomials $f = a_0 + \dots + a_nx^n \in R[X]$ define functions $f:R\rightarrow R$ by $f(a) = a_0 + a_1a + \dots + a_na^n$. If $f(a) = 0$, we say $a$ is a *root* of $f$.

Prime elements in $R$ are also prime elements in $R[X]$ ([[Irreducible and Prime Elements]]).

#### Derivative
The derivative of a polynomial $f = a_0 + \dots + a_nx^n$ is defined as $f^{\prime} = a_1 + \dots = a_nx^{n-1}$.
If $f$ is a polynomial in $X_1,\dots,X_n$, then the *partial derivative* with respect to $X_i$ is the derivative of $f$ considering $X_j$ with $j\neq i$ as constants and $X_i$ as the only unknown.

#### Discriminant

For a polynomial $f\in R[X]$ with $f = a_0 + a_1X + \dots a_{n-1}X^{n-1} + X^n$ we define
$\Delta(X_1,\dots,X_n) = \Pi_{1\leq i < j \leq n} (X_i-X_j)^2$.
If $f$ has roots $t_1,\dots,t_n$ (not necessarily in $R$), then the *discriminant* of $f$ is $\Delta(f) = \Delta(t_1,\dots,t_n)$

#### Content of a Polynomial

If $R$ is a [[Factorial Ring]] and $f = a_0+a_1x+\dots+a_nx^n\in R[x]$, then $I(f) = gcd(a_0,\dots,a_n)$ is called the *content* of $f$.
We have $I(fg) \sim I(f)I(g)$ ([[Ring#Associated Elements]])

For a polynomial $f\in R[X]$ with $I(f)=1$ we have 
1. $f$ irreducible in $R[X]$ $\Rightarrow$ $f$ irreduzible in $Q(R)[X]$ ([[Quotient Field]])
2. $f$ is a divisor of $g\in R[X]$ in $Q(R)[X]$ $\Rightarrow$ $f$ is a divisor of $g$ in $R[X]$ ([[Ring#Divisors]]) 
3. $f$ is irreducible in $Q(R)[X]$ $\Rightarrow$ $f$ is prime in $R[X]$ 

From that, we get the following: 

if $\frac{a}{b} \in Q(R)$ is a root of $f = a_0 + \dots + a_nX^n \in R[X]$, then $l(X) = (bX-a)$ is a divisor of $f$ in $R[X]$ 


#### Reduction Theorem

For a factorial ring $R$ and integral domain ([[Ring#Zero Divisors]]) $S$ with [[Ring Homomorphism]] $\varphi : R\rightarrow S$ , we can extend $\varphi$ to a homomorphism $R[X]\rightarrow S[X]$ via

$\varphi(\sum_{i=0}^n a_ix^i) = \sum_{i=0}^n \varphi(a_i)x^i$ 

If $f\in R[X]$ has $I(f)=1$ with $\varphi(f)$ is irreducible in $S[X]$ and $degf = deg\varphi(f$), then $f$ is irreducible in $R[X]$.


#### Gauss' Theorem

If $R$ is factorial, $R[X]$ is factorial.

### [[Graded Ring]]

If we let $S_d\subseteq R[X_1,\dots,X_n]$ be the set of all linear combinations of monomials with total weight $d$, then $R[X_1,\dots,X_n]$ is a graded ring. 
For homogeneous polynomials (i.e. ones in $S_d$) we have $f(\lambda a_0,\dots,\lambda a_n) = \lambda^d f(a_0,\dots,a_n)$