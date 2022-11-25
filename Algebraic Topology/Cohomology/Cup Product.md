If we have [[Cohomology]] groups $H^n(X;R)$ with $R$ a [[Ring]], the *cup product* $\smile$ is defined as 

$$ C^k(X;R)\times C^l(X;R) \rightarrow C^{k+l}(X;R)$$
$$(\varphi \smile \psi)(\sigma) = \varphi(\sigma|_{[v_0,\dots,v_k]})\psi(\sigma|_{[v_k,\dots,v_{k+l}]})$$
Where $C^n(X;R)$ are the cochain groups ([[Chain Complexes#Cochain Complex]]) of $X$ with coefficients in $R$.

We have $\delta(\varphi \smile \psi) = \delta \varphi \smile \psi + (-1)^k \varphi \smile \delta \psi$ , and can therefore excend the cup product to cohomology groups $H^k(X;R)\times H^l(X;R)\rightarrow H^{k+l}(X;R)$.
SImilarly, there is the relative cup product ([[Cohomology#Relative Cohomology Groups]]) 

$$ H^k(X,A;R)\times H^l(X,B;R) \xrightarrow{\smile} H^{k+l}(X,A\cup B;R)$$

For induced maps $f^*$ on cohomology from $f:X\rightarrow Y$, we have $f^*(\alpha \smile \beta) = f^*(\alpha) \smile f^*(\beta)$ on absolute and relative cohomology.

The identity $\alpha \smile \beta - (-1)^{kl}\beta \smile \alpha$ holds if $R$ is a commutative ring.