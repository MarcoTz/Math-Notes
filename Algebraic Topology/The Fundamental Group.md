Given a [[Topological Space]] $X$ and a point $x_0\in X$ we denote the set of homotopy classes ([[Homotopy#Homotopy of Paths]]) of loops ([[Continous Function#Paths]]) with endpoint $x_0$ by $\pi_1(X,x_0)$.

Given two loops $f,g:I\rightarrow X$ with endpoint $x_0$, we defined the product $f\cdot g$ as the loop

$$ f\cdot g(s) = \left\{ \begin{array}{cc} f(2s) & 0\leq s\leq \frac{1}{2} \\g(2s-1) & \frac{1}{2} \leq s \leq 1 \end{array}\right. $$
since $f(1)=g(0)$, this is a well-defined loop with endpoint $x_0$. 
With the product $[f][g]=[fg]$, $\pi_1(X,x_0)$ defines a [[group]] with identity the class of the constant path $c(t) = x_0 \forall t$ and inverses $[\bar{f}]$ where $\bar{f}(t) = f(1-t)$.
We call this group *the fundamental group of X at x_0*.
For any group $G$, there is a topological space $X$, with $\pi_1(X)\cong G$.

### Change of Basepoint map

Given a path $h:I\rightarrow X$ with endpoints $x_0$ and $x_1$ and a loop $f:I\rightarrow X$ with endpoint $x_0$, the product $h\cdot f\cdot \bar{h}$ defines a loop at $y_0$.
We call the map $\beta_h : \pi(X,x_1)\rightarrow \pi(X,x_0)$ the *change of basepoint map*. It defines an isomorphism of fundamental groups.

If $X$ is path-connected ([[Path Connectedness]]) the groups $\pi_1(X,x_0)$ and $\pi(X,x_1)$ are isomorphic for any $x_0,x_1\in X$, so we often just write $\pi_1(X)$ in this case.

### Simply Connected Spaces 

A topological space is called *simply-connected* if it is path-connected and has trivial fundamental group.

### Spheres

The fundamental groups of [[Spheres]]  $S^n$ is trivial for $n>1$ and $\mathbb{Z}$ for $n=1$.

### Products 

$\pi_1(X\times Y) \cong \pi_1(X)\times \pi_1(Y)$ iff $X$ and $Y$ are path-connected.

### Induced Homomorophisms

Given a continous map $f:(X,x_0)\rightarrow (Y,y_0)$, there is an *induced homomorphism* $f_*:\pi_1(X,x_0)\rightarrow \pi_1(Y,y_0)$ given by $f_*([g]) = [g\circ f]$. This homomorphism has the following properties 

* $(\varphi\psi)_* = \varphi_*\psi_*$ for a composition $(X,x_0)\xrightarrow{\psi} (Y,y_0) \xrightarrow{\varphi} (Z,z_0)$ 
* $\mathbb{1}_*=\mathbb{1}$ 