A set ([[Sets]]) $X$ with a function $d:X\times X\rightarrow \mathbb{R}$ ([[Real Numbers]]) satisfying the following properties 

1. $d(x,x) = 0 \forall x\in X$
2. Positivity: $x\neq y \Rightarrow d(x,y)>0 \\forall x,y\in X$
3. Symmetry: $d(x,y) = d(y,x) \forall x,y\in X$
4. Triangle Inequality: $d(x,y)\leq d(x,y) + d(x,z) \forall x,y,z\in X$


is called a *metric space*.
Any metric space is also a [[Topological Space]] with open sets defined as the *open balls* with positive radius around any point $x$: $B_r(x) = \{y\in X | d(x,y)<r\} \quad \forall x\in X, r>0$


If $f:A\rightarrow Y$ is [[Continous Function]], $A\subseteq X$, and $Y$ is a metric space, then there is a unique map $\bar{f}:X\rightarrow Y$ that is continous and $\bar{f}|_A = f$.