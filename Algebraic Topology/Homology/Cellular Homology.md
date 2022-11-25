If $X$ is a CW complex ([[Cell Complexes]]) then we have the following properties of [[Singular Homology]]

1. $H_k(X^n,X^{n-1})$ is $0$ for $n\neq k$ and a free ([[Free Groups]]) [[Abelian Group]] with generators in 1-1 correspondence to $n$-cells of $X$.
2. $H_k(X^n)=0$ for $k>n$ 
3. The map $H_k(X^n)\rightarrow H_k(X)$ induced by the inclusion $X^n\hookrightarrow X$ is an isomorphism for $k<n$ and surjective for $k=n$

With these properties we get the following *cellular chain complex* ([[Chain Complexes]])

$$ \dots \rightarrow H_{n+1} (X^{n+1},X^n)\xrightarrow{d_{n+1}} H_n(X^n,X^{n-1}) \xrightarrow{d_n} H_{n-1}(X^{n-1},X^{n-2})$$

The boudary maps $d_n$ are defined as the compositions $j_{n-1}\partial_n$ where $j_{n-1}$ is from relative homology ([[Relative Homology]]).
The homology groups from this chain complex are called *cellular homology groups* denoted by $H_n^{CW}(X)$ and we have 

$$H_n^{CW}(X) \cong H_n(X)$$

### Cellular Boundary Formula

$$ d_n(e^n_{\alpha}) = \sum_{\beta}d_{\alpha\beta}e_{\beta}^{n-1} $$ where $d_{\alpha\beta}$ is the degree ([[Spheres#Degree]]) of the map $S_{\alpha}^{n-1}\rightarrow X^{n-1}\rightarrow S_{\beta}^{n-1}$ that is the composition of the attaching map of $e_{\alpha}^n$ with the quotient map ([[Topology/Quotient Space#Quotient Maps]]) collapsing $X^{n-1}\setminus e_{\beta}^{n-1}$ to a point. 